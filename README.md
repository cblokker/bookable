# BOOKABLE


## 🎉 [Live Demo on heroku](https://bookingclient-0e4fee061c97.herokuapp.com/)
(no need for local setup to test functionality)


## Assumptions

### Implied User Research
1. **Coach-Centric Availability Management**:
   - Coaches prefer managing their **availability** rather than micromanaging individual slots.
   - The system interprets an **availability window** as a range of time during which multiple slots can be inferred.
     - **Example**: A coach sets a 2-hour availability window (e.g., 9 AM–11 AM), which is divided into smaller, bookable slots.
   - Future flexibility: The design supports adding **booking types**:
     - Morning: 30-minute slots.
     - Afternoon: 2-hour slots.
   - Availability management is envisioned as a **dashboard** for easy updates and recurring schedules.

2. **Student-Focused Booking Experience**:
   - Students prioritize the **coach** over other booking criteria (e.g., time or meeting type). Imagine having preferred coaches.
   - The booking flow is designed as a **multi-step form**, focusing on coach selection first:
     1. Select a coach.
     2. Choose a meeting type.
     3. Select an available time.
     4. Confirm the booking.


## TODO

- Review the **comments in the code** for further implementation tasks. Grep TODO.

## PRD & TRD?
Let's discuss in person :)

