---
title: "ENS Lyon PINNs Group Meeting"
permalink: /pinns-group-meeting/
layout: single
author_profile: false
---

A working group on Physics-Informed Neural Networks (PINNs) and, more
broadly, on neural-network-based numerical methods for PDEs.

The group holds regular meetings, in a fairly informal format, to present
work in progress, discuss scientific and technical questions, and encourage
exchange between people interested in these topics.

**Organizers:** [Antoine Venaille](https://perso.ens-lyon.fr/antoine.venaille/), [Elisa Riccietti](https://perso.ens-lyon.fr/elisa.riccietti/), [Nelly Pustelnik](https://perso.ens-lyon.fr/nelly.pustelnik/), and [Nilo Schwencke](https://nilo.schwencke.me).

**Location:** Room M7 101

**Time:** Friday 2pm on selected dates \(see calendar below\)

## Mailing list

A mailing list has been set up for the group. Subscribe here:

[Subscribe to the mailing list](https://listes.ens-lyon.fr/sympa/subscribe/pinns-group-meeting)

## Calendar

<!-- TODO: the underlying Zimbra calendar is currently empty -- sessions will
     appear here automatically once added on the Zimbra side. The embedded
     view below is server-rendered by Zimbra and follows the calendar
     account's own locale (French month/day label inside the grid), which
     cannot be overridden from this page. Month navigation is handled by the
     small JS snippet below (Zimbra's own toolbar, which included the
     prev/next arrows, was stripped via notoolbar=1 to avoid its French
     button labels; this replaces it with English controls). -->

<div style="display:flex; gap:0.5rem; align-items:center; margin-bottom:0.5rem;">
  <button type="button" id="pinns-cal-prev" aria-label="Previous month">&larr; Previous</button>
  <button type="button" id="pinns-cal-today">Today</button>
  <button type="button" id="pinns-cal-next" aria-label="Next month">Next &rarr;</button>
  <span id="pinns-cal-label" style="margin-left:auto; font-weight:600;"></span>
</div>

<iframe
  id="pinns-cal-iframe"
  src=""
  title="PINNs Group Meeting calendar"
  style="width: 100%; height: 666px; border: 1px solid #ddd; border-radius: 4px;"
  loading="lazy">
</iframe>

<script>
(function () {
  var base = "https://zimbra.inria.fr/home/nilo-elias.schwencke@inria.fr/Group%20meeting%20PINNs.html?view=month&notoolbar=1";
  var iframe = document.getElementById("pinns-cal-iframe");
  var label = document.getElementById("pinns-cal-label");
  var current = new Date();
  current.setDate(1);

  var monthNames = ["January", "February", "March", "April", "May", "June",
    "July", "August", "September", "October", "November", "December"];

  function pad(n) { return n < 10 ? "0" + n : "" + n; }

  function render() {
    var y = current.getFullYear();
    var m = current.getMonth() + 1;
    iframe.src = base + "&date=" + y + pad(m) + "01";
    label.textContent = monthNames[current.getMonth()] + " " + y;
  }

  document.getElementById("pinns-cal-prev").addEventListener("click", function () {
    current.setMonth(current.getMonth() - 1);
    render();
  });
  document.getElementById("pinns-cal-next").addEventListener("click", function () {
    current.setMonth(current.getMonth() + 1);
    render();
  });
  document.getElementById("pinns-cal-today").addEventListener("click", function () {
    current = new Date();
    current.setDate(1);
    render();
  });

  render();
})();
</script>

This calendar is kept in sync with the group's Zimbra calendar. You can also
subscribe to it directly in your own calendar app:

- [Subscribe (Outlook / Apple Calendar)](webcals://zimbra.inria.fr/home/nilo-elias.schwencke@inria.fr/Group%20meeting%20PINNs)
- [Download .ics](https://zimbra.inria.fr/home/nilo-elias.schwencke@inria.fr/Group%20meeting%20PINNs.ics)
- [Open full calendar view](https://zimbra.inria.fr/home/nilo-elias.schwencke@inria.fr/Group%20meeting%20PINNs.html){:target="_blank"}

## Upcoming talks

For this first series of meetings, the following dates are confirmed. Times,
locations, and titles will be announced shortly, both here and on the
mailing list.

| Date | Speaker | Details |
|---|---|---|
| November 6, 2026 | Andrea Combette | [page]({{ base_path }}/pinns-group-meeting/andrea-combette/) |
| November 20, 2026 | Corentin Herbert | [page]({{ base_path }}/pinns-group-meeting/corentin-herbert/) |
| December 4, 2026 | Nilo Schwencke | [page]({{ base_path }}/pinns-group-meeting/nilo-schwencke/) |

## Want to present?

If you would like to present your work or suggest a discussion topic for a
future session, please get in touch via the mailing list or contact the
organizers directly.
