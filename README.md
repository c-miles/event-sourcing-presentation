# From CRUD to Events: A Rails Developer's Journey into Event Sourcing

A technical presentation exploring Event Sourcing, CQRS, and event-driven architecture patterns with practical Rails examples.

## Overview

This presentation introduces Event Sourcing as an architectural pattern for capturing all changes to application state as a sequence of events. It covers the motivation, implementation, and practical considerations for adopting Event Sourcing in Rails applications.

## Topics Covered

- Traditional CRUD limitations and lost historical context
- Event-driven patterns: Event Notification, Event-Carried State Transfer, CQRS, and Event Sourcing
- Core concepts: Commands, Events, Deciders, Reactors, Event Stores, and Read Models
- Rails implementation with PostgreSQL
- Benefits: Time travel queries, audit trails, replay debugging, and event-driven architecture
- Real-world trade-offs and when to use Event Sourcing

## Theoretical Foundation

This presentation draws primarily from foundational work by Martin Fowler (martinfowler.com/eaaDev/EventSourcing.html), Greg Young (CQRS pattern creator), and Vaughn Vernon (Domain-Driven Design). Additional insights come from Rails Event Store and implementation experience at Kode Health.

## Technology Stack

- **Reveal.js 5.0.4** - HTML presentation framework
- **Highlight.js** - Code syntax highlighting (Monokai theme)
- **Custom Ruby ASCII Animation** - Port of IRB's easter egg animation

## Running the Presentation

Self-contained HTML file with no build process required.

```bash
# Open directly
open event-sourcing-presentation.html

# Or use local server (recommended)
python3 -m http.server 8000
# Navigate to: http://localhost:8000/event-sourcing-presentation.html
```

## Navigation

- Arrow keys: Navigate slides
- `g`: First slide | `e`: End slide | `j`: Jump to slide
- `o`: Overview mode | `s`: Scroll view | `?`: Help
- `ESC`: Exit overview mode

## Browser Compatibility

Requires modern browsers with ES6+ support (Chrome, Firefox, Safari, Edge latest versions).

## Credits

**Presenter**: Chris Miles (cw.miles121@gmail.com)

**ASCII Animation**: Faithful port of Ruby's IRB easter egg (`IRB.send(:easter_egg)`) with 3D vector math, backface culling, and sub-pixel rendering.
