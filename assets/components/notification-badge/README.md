# Notification badge

A notification badge shows a number.

{{ example("notification-badge.html", scaled=false, cy=false, html=false) }}

## When to use this component

Use a notification badge to grab attention and show how many things something has and. Only use it with an action someone can do to change the number.

### When not to use this component

Do not use a notification badge when:

- the number of things is 0
- there is no action

Unless there is a strong user need, only use one as a part of navigation.

## How it works

A notification badge displays a number on the right-hand side of an action.

If the number is more than 99, display “99+”.

{{ example("notification-badge.html", scaled=false, cy=false, html=true) }}

If there are 0 things, do not show the badge.

{{ example("notification-badge-zero.html", scaled=false, cy=false, html=true) }}

## Research on this component

Notification badges are common on many sites and services. It is part of the [Account header](components/account-header/index.html). Research showed:

- people understand what it is for
- it does not distract people from their task

{{ research(142) }}