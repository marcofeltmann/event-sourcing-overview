# Slides

Deckset.app, but which theme?

# Agenda

The estimation is 45 minutes.  
Chances are there will be questions afterwards, so I should be somewhat faster.  
The schedule includes the app demonstration, too…

## According to appointment

Event Sourcing Overview:

- What it means
    - Keyboard and Mouse events
    - Bank account transactions
- How we technically realize it
    - Pub/Sub with NATS (one might use NSQ as well)
    - Persistent Consumer with JetStream (one might create some own as well)
- What we already do with it
    - Nothing, err, something (WIP, Pre-Beta)
    - some other thing (WRIP, Pre-Alpha…)
- How a simple e-commerce flow might look like
    - Structure roughly stolen by Greg Youngs "Shipping Informat ion added" talk
    - Sample App
- Room for questions
    - ¿Y U NO database?
    	- Well, you could and should for state. You might also snapshot. But it's not the truth, just some state.

