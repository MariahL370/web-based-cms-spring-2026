---
title: API Reference
author: Mariah Lopez
status: draft
audience: developers
tags: [api, authentication]
---
# API Reference

## API Overview

The Acme Corp API v2 allows developers to update user profile preferences through a secure endpoint. This includes features such as theme selection and notification settings.

This API follows REST principles and uses JSON for both requests and responses.

---

## Authentication

This endpoint requires authentication using a Bearer Token. Include your token in the `Authorization` header for all requests.

### Example

```http
Authorization: Bearer YOUR_API_TOKEN

## Endpoint

POST /api/v2/users/preferences