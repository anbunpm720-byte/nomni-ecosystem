# NOMNI – API CONTRACT

## Project
NOMNI – AI Powered Lifestyle and Commerce Ecosystem

## Architecture
- Frontend: React + TypeScript
- Backend: Node.js + Express + TypeScript
- Database: PostgreSQL / Supabase
- AI: Fashion design generation API
- Payment: PayPal Sandbox

## API Base URL
`/api`

## 1. Authentication
- POST `/api/auth/register`
- POST `/api/auth/login`
- GET `/api/auth/profile`

## 2. NOMNI Fresh
- GET `/api/fresh/products`
- POST `/api/fresh/products`
- GET `/api/fresh/products/:id`

## 3. NOMNI Forge
- GET `/api/forge/products`
- POST `/api/forge/products`
- GET `/api/forge/products/:id`

## 4. NOMNI Fashion
- GET `/api/fashion/designers`
- GET `/api/fashion/tailors`
- POST `/api/ai/design`
- GET `/api/ai/designs`

## 5. Cart and Orders
- GET `/api/cart`
- POST `/api/cart`
- POST `/api/orders`
- GET `/api/orders`

## 6. Payments
- POST `/api/payments/create`
- POST `/api/payments/capture`

## Team Responsibilities
- Member 1: Frontend
- Member 2: Backend and Database
- Member 3: AI and PayPal Integration

## Integration Rules
1. All members must follow this API contract.
2. Agree on request and response formats before implementation.
3. Never expose API keys or secrets in frontend code.
4. Payment confirmation must happen only after backend verification.
5. Each member must work on their own Git branch.
6. Final integration will be tested before deployment.

## Important
This document defines the initial API plan. The team must confirm request/response formats and endpoint ownership before implementation.
