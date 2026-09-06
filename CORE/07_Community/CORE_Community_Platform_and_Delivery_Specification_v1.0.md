# CORE™ Community Platform & Delivery Specification v1.0

**Status:** CURRENT / IMPLEMENTATION SPECIFICATION  
**Parent:** CORE™ Community Architecture v1.0  
**Purpose:** Translate Decide With CORE into an implementable owned-web/platform experience, with Graphy considered as a delivery layer.

## 1. Platform principle

The platform should feel like **CORE**, not like a course-hosting vendor.

Technology is infrastructure.

The customer should experience:

> **community + knowledge + application + participation**

## 2. Product structure

### Public website

Hosts:

- brand and positioning
- public content
- public publications
- offers
- cases
- entry points
- community invitation

### Member environment

Hosts:

- premium content
- Decide+
- scenarios
- live sessions
- member discussions
- resources
- archives
- profile / discovery

## 3. Preferred commercial product structure

### Entry

**₹499**

Open purchase.

### Community

**₹7,999 one-time**

**Decide With CORE** access.

### Advanced programme

**₹39,999 Idea → Market**

Purchasable only by authenticated community members.

### Enterprise

**₹5L**

Handled as a qualified commercial engagement.

## 4. Required access states

The platform needs at minimum:

```text
Visitor
↓
₹499 Customer
↓
Community Member
↓
₹39,999 Participant
↓
Enterprise / Advisory Client
```

These are customer states, not necessarily mutually exclusive account types.

## 5. Community navigation

Recommended primary structure:

```text
Home
Explore
Decide+
Signals & Strategy
Ideas for Enduring Advantage
Strategic Systems Thinking
Manufacturing Strategy Series
Confluence of Enterprise Capabilities
Scenarios
Live
Community
Library
Profile
```

The final navigation should be simplified after observing real usage.

## 6. Content architecture

Every premium asset should have metadata such as:

- channel
- theme
- content type
- industry
- business situation
- maturity/state
- related product
- scenario ID if applicable
- publish date
- access level

## 7. Membership access control

The system must verify:

> **Is the user an active Decide With CORE member?**

For ₹39,999 purchase:

> **Community member = eligible to purchase**

If the platform cannot enforce this natively, implement the eligibility check using the available payment, account or workflow layer rather than relying on a visible discount code alone.

## 8. Graphy role

Graphy may function as the learning/community delivery infrastructure if it can satisfy the required experience.

Graphy should not determine the intellectual architecture.

The system remains:

> **CORE architecture → platform implementation**

## 9. Functional requirements

The platform should support, directly or through integrated tools:

- one-time community purchase
- member authentication
- premium content access
- course delivery
- live session management
- discussion/community features
- content search or structured archives
- member profiles
- email notifications
- event reminders
- analytics
- purchase history
- access control
- export/back-up of member and content data where available

## 10. Email system

Required transactional and lifecycle email categories:

### Transactional

- purchase confirmation
- access instructions
- password/login
- course access
- live-session details

### Community lifecycle

- welcome
- orientation
- important new scenario
- live-room reminder
- monthly synthesis
- relevant product invitation

Email should add utility rather than become a broadcast dump.

## 11. Analytics

Track:

- acquisition source
- community conversion
- active members
- participation
- scenario participation
- live attendance
- Decide+ use
- content engagement
- member-to-member activity where measurable
- ₹39,999 progression
- downstream commercial outcomes

## 12. Governance

The platform should maintain clear ownership for:

- content
- member data
- access permissions
- payment records
- community moderation
- intellectual property
- privacy
- backups
- exports

## 13. Data and privacy

Collect the minimum data necessary to provide the service.

Member information should not be used for unrelated marketing or exposed beyond the community purpose without an appropriate basis and notice.

## 14. Implementation sequence

### Phase 1

- public website
- community purchase
- member login
- premium content area
- Decide+
- basic discussion/community

### Phase 2

- scenarios
- live rooms
- profiles
- archives
- member discovery

### Phase 3

- better search
- recommendation
- member matching
- intelligence dashboards
- deeper integrations

Do not overbuild Phase 1.

## 15. Platform acceptance test

The implementation is ready when a new member can:

> discover → buy → enter → understand where to start → consume one useful asset → participate → find a relevant person/session/scenario → return.

## 16. Platform principle

> **Own the customer relationship and experience; use platforms as replaceable infrastructure.**
