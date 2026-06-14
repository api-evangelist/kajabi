# Kajabi GraphQL Schema

## Overview

This document describes a conceptual GraphQL schema for the Kajabi creator and online course platform. Kajabi's public API is RESTful (base URL: `https://api.kajabi.com/v1`, OAuth 2.0 required on the Pro plan), but this schema translates its core domain model into GraphQL types covering products, courses, communities, email marketing, members, offers, transactions, and platform configuration.

## Source

- Developer documentation: https://developers.kajabi.com/
- API reference: https://help.kajabi.com/api-reference/introduction
- OpenAPI specification: https://github.com/Kajabi/public_api_docs/blob/main/openapi.yaml

## Schema Source

Conceptual — derived from the Kajabi REST API surface, developer documentation, and the published OpenAPI specification. Kajabi does not expose a native GraphQL endpoint.

## Type Summary

| Domain | Types |
|---|---|
| Products | Product, ProductDetails, ProductType, ProductStatus |
| Courses | Course, CourseDetails, CourseModule, ModuleDetails, Lesson, LessonDetails, LessonType, LessonContent |
| Communities | Community, CommunityDetails, Post, PostDetails, Category, CategoryDetails |
| Coaching | Coaching, CoachingDetails, CoachingSession |
| Podcasts | Podcast, PodcastDetails, Episode, EpisodeDetails |
| Email Marketing | Email, EmailDetails, EmailTemplate, Campaign, CampaignDetails, Broadcast, BroadcastDetails, Sequence, SequenceDetails |
| Automations | Automation, AutomationDetails, AutomationEvent |
| Members | Member, MemberDetails, MemberStatus |
| Offers & Pricing | Offer, OfferDetails, OfferType, Price, PriceDetails |
| Subscriptions | Subscription, SubscriptionDetails, SubscriptionStatus |
| Transactions | Transaction, TransactionDetails |
| Customers | Customer, CustomerDetails |
| Forms & Pipelines | Form, FormDetails, Pipeline, PipelineDetails |
| Platform | APIKey, Token, Webhook |

## Total Named Types

62 named types (scalars, enums, interfaces, and object types combined).

## Authentication

GraphQL operations would require OAuth 2.0 bearer tokens obtained through the standard Kajabi OAuth flow. The `Authorization: Bearer <token>` header applies to all queries and mutations.

## Design Notes

- Enums represent closed-value fields (status, type) from REST response payloads.
- Interfaces (`Node`, `Timestamped`) capture shared identity and audit fields.
- Connections follow the Relay cursor pagination convention.
- Mutations mirror the POST/PUT/PATCH/DELETE endpoints in the REST API.
- All IDs are global Relay-style node IDs encoded as `ID` scalars.
