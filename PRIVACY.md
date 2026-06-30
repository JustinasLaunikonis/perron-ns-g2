# Privacy Policy — Perron-NS

**Last updated: 28 June 2026**

Perron-NS ("the app") is a journey planner for Dutch Railways (NS) services,
built for Even Realities G2 glasses and the Even Hub platform. This policy
explains what data the app handles, why, and who it is shared with.

The app has **no user accounts, no advertising, no analytics, and no tracking.**
It does not sell or share personal data, and it collects no more than is needed
to plan a journey.

## Data stored on your device

The following are saved **locally on your device** (via the browser
`localStorage` API) and are never uploaded to us:

- **Favorite locations** — stations you choose to save, including any custom
  label and icon you set.
- **Recent journeys** — the "Plan again" history of from/to routes you have
  planned.

This data stays on your device. Removing the app, clearing its storage, or
deleting individual favorites/routes inside the app erases it. We cannot see it
and have no copy of it.

## Data sent over the network

To show live travel information, the app sends the following to our backend
proxy when you search or plan a journey:

- The text you type to search for a station, and the station codes you select.
- The origin and destination station codes for a journey you plan.

This data is used only to retrieve station lists, departure boards, and journey
options. It is **not** linked to your identity, stored by the app's backend, or
used for any other purpose.

### Why the app needs network access

The app declares a single **network** permission. It is used solely to fetch
Dutch Railways (NS) station, departure, and journey-planning data through the
backend described below. The app makes no other network connections.

## Third parties

Network requests reach NS through one intermediary service that we operate:

- **Backend proxy:** `https://perron-ns-proxy.justinasla.workers.dev`
  Operated by us and hosted on Cloudflare Workers. It forwards your requests to
  the NS Reisinformatie API and attaches the NS API key on the server side (the
  key is never included in the app). The proxy does not store the contents of
  your requests. As with any internet service, the hosting provider
  (Cloudflare) may process standard request metadata such as IP address
  transiently to deliver and protect the service. See Cloudflare's privacy
  policy: https://www.cloudflare.com/privacypolicy/

- **NS Reisinformatie API** (`gateway.apiportal.ns.nl`), operated by
  Nederlandse Spoorwegen (NS). The station codes for your query are sent here so
  NS can return the matching travel information. NS processes this data under
  its own privacy policy: https://www.ns.nl/en/privacy

We do not share your data with anyone else.

## Data retention

- On-device data (favorites, recent journeys) is kept until you delete it or
  remove the app.
- The app's backend proxy does not retain the contents of your requests.

## Children

The app is a general-audience travel tool and is not directed at children. It
does not knowingly collect personal information from children.

## Changes to this policy

If this policy changes, the "Last updated" date above will change and the
revised policy will be published at the same location as this document.

## Contact

Questions about this policy or your data:

**Justinas Launikonis** — justinas.launikonis@student.nhlstenden.com
