# EuropeMaps support

[Store listing](https://apps.garmin.com/apps/f5cd5919-84f9-41b3-b5c7-276a154039bc) · [Setup guide](SETUP.md) · [Maps & Routes](https://europemaps.duckdns.org/routes)

## No map after installation

No map is bundled. Open Garmin Connect on the phone and EuropeMaps on the watch, then choose **MENU → Download maps → Choose on phone**. Follow the [setup guide](SETUP.md).

## No phone link or code request stopped

Open **Garmin Connect**, rather than only the Connect IQ Store, and keep it in the foreground. Confirm phone internet and watch connectivity. With the code showing, press GPS to retry the link, or open the website manually and type the code. The browser is your phone's configured default; Garmin's own confirmation wording can vary.

A negative communications status such as **-300** may indicate a phone/Connect communications interruption. Reconnect and retry with Connect open. Do not uninstall as the first troubleshooting step: it removes local data and changes the installation credentials.

## Website search does not change the map

After searching, tap the intended result below the search field. You can also tap the map directly, with no search required. Check the coverage outline, then start the transfer; **Check coverage** alone does not download the area.

## Invalid or expired code / too many requests

Codes expire after ten minutes and are used for one transfer. Keep the watch on the current code screen and use that code. If it has expired or was already used, generate a new one. Respect a request-limit message and wait before trying again; repeated checks can reach protective limits.

## Transfer stalls or stops

Keep EuropeMaps open and the phone connected with internet access. Return from the browser to Garmin Connect. If standby interrupts the download, leave Connect in the foreground. Large areas need many requests and can take several minutes; start with 2 × 2 km. Do not assume the website's “Transfer sent” message means every map piece is already on the watch.

## Server paused / quota / HTTP 403

The service has shared and per-installation protection limits. A 403 is a refusal, not proof of a GPS problem. Read the exact accompanying message. Try later if a limit is reached or the service is paused. Saved maps remain usable. Public users should not need private-beta approval; include the app build in a report if that message appears.

## No GPS or uncertain heading

Go outdoors with a clear sky view and allow time for reception. Use North up if direction is unavailable. Activity recording waits for a usable GPS fix. A planned GPX route does not correct the measured GPS track.

## The map is away from my position

Choose **MENU → Recenter** to resume following your position. **Show map centre** moves to the downloaded area's centre instead. Your position must be inside installed coverage to see nearby roads. Selecting a saved route with **Use route** loads its matching corridor.

## Route deletion and storage

A linked route's **Delete route + map** removes that route and corridor. Saved maps and route corridors share app storage and the five-entry allowance. Remove unused entries if a large download will not fit. Current versions support re-importing a route after deleting it.

## Missing detail or an IQ! crash

Maps and names are simplified and detail varies with location and scale. For a crash, report the exact steps, zoom scale, orientation, watch model/firmware and EuropeMaps build. If available, include the relevant Error block from GARMIN/APPS/LOGS/CIQ_LOG.YAML, after checking it for private information. A simulator check cannot rule out every physical-watch issue.

## Contact

[Open a GitHub issue](https://github.com/Asparaguss/europemaps/issues/new/choose) or email [asparaguss@proton.me](mailto:asparaguss@proton.me). Include watch model/size, app build, phone platform, exact error and reproduction steps.

Public issues are visible to everyone. Do not post pairing codes, access secrets or private GPX/FIT tracks. Use email if your report requires private location details.

[Privacy policy](https://asparaguss.github.io/europemaps/)
