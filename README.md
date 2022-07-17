# **Ticketing - Common Library**

Contains commonly used errors, events, types, classes, interfaces and middlewares for [ticketing](https://github.com/dudakovict/ticketing) microservices.

## Errors
- [BadRequestError](src/errors/bad-request-error.ts)
- [CustomError](src/errors/custom-error.ts)
- [DatabaseConnectionError](src/errors/database-connection-error.ts)
- [NotAuthorizedError](src/errors/not-authorized-error.ts)
- [NotFoundError](src/errors/not-found-error.ts)
- [RequestValidationError](src/errors/request-validation-error.ts)
  
## Events
### Base
- [Listener](src/events/base/listener.ts)
- [Publisher](src/events/base/publisher.ts)
- [Subjects](src/events/base/subjects.ts)
### Services
#### Expiration
- [ExpirationCompleteEvent](src/events/services/expiration/expiration-complete-event.ts)
#### Orders
- [OrderCancelledEvent](src/events/services/orders/order-cancelled-event.ts)
- [OrderCreatedEvent](src/events/services/orders/order-created-event.ts)
#### Payments
- [PaymentCreatedEvent](src/events/services/payments/payment-created-event.ts)
#### Tickets
- [TicketCreatedEvent](src/events/services/tickets/ticket-created-event.ts)
- [TicketUpdatedEvent](src/events/services/tickets/ticket-updated-event.ts)
### Types
- [OrderStatus](src/events/types/order-status.ts)
  
## Middlewares
- [CurrentUser](src/middlewares/current-user.ts)
- [ErrorHandler](src/middlewares/error-handler.ts)
- [RequireAuth](src/middlewares/require-auth.ts)
- [ValidateRequest](src/middlewares/validate-request.ts)

## Exports
- [Index](src/index.ts)

## License
[MIT](LICENSE)
