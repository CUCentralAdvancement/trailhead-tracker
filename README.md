# trailhead-tracker
PoC application to track a team's Trailhead points and badges over time

* [ ] Create a list of the Trailhead usernames of team members we’d like to track. Format this a JSON and include in app for MVP
* [ ] For each team memebr, get current data from Trailhead using API (or scrape?)
* [ ] Add record to Postgres in private space using API Platform endpoints
* [ ] Run this on cron once a day by checking every hour if it has been successfully in the last 24 hours. Keep track of fails. Send email after 3.
* [ ] If the valued change, update the user’s profile on a Salesforce sandbox instance using API and/or Heroku Connect
* [ ] Create a UI to track points and badges over time on Heroku dyno using API platform data.
* [ ] Add a link to the visualization of the badges over time in the user’s profile.
