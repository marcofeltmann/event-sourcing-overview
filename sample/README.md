# Sample App

Required to somewhat support the slides.

# Tech Stack

Go and Fyne  
I want to learn things, right?!

# Business Case

E-Commerce stuff.  

- Unregistered
- Adding and removing stuff to and from cart
- Check out cart
- Shipping Information input
- Payment processing stuff
- Successful order summary

Screens:

- Welcome Screen
- Products Screen
- Cart Screen
- Shipping Information Screen
- Payment Information Screen
- Order Completion Screen

Events:

- e-commerce events for each stuff
- screen events for each screen

Usage:

- You type stuff in each screen (e-commerce event + screen event per screen)
- Created events are shown
- Event indicator sliders are updated
- Sliding event indicator sliders will run through all the corresponding events

Event Implications:

- Linked events (containing an "inverse" event)
- `screen.changed` event with Screen Identifier as Payload
- `welcome.continued` event
- `product.added`, `product.removed` and `product.completed` event
- `cart.product.added`, `cart.product.removed` and `cart.checkout` event
- `shipping.name.changed`, `shipping.address.changed`, `shipping.mail.changed` and `shipping.submitted` event
- `payment.method.selected`, `payment.agb.accepted`, `payment.submitted` and `payment.completed` event
- `order.received` event
