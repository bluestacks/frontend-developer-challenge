# Frontend Developer Challenge 

Implement a web page, which contains 3 tabs (Upcoming Campaigns, Live Campaign, Past campaigns) as defined in
the following mockup.

* Each tab should show relevant data based on the status of campaign (upcoming, live, past).
* The very first column should show the time diff from today to that campaign's date. (You can consider
any date. If the date is in the future, you can show the number of days in the future. For example, **"23
days ahead"**)
* Add functionality to reschedule a campaign by opening a calendar on clicking the schedule
again icon. (Whatever date you select, should be shown in the first column named **"Date"**. The
time diff shown against it should also be updated)
* Clicking on any item in the row should show a modal with relevant information. See the design in the Specs section below 
* Entire UI should be responsive.
* UI should be same regarding color schemes and layout, button states etc. The assets are provided in the Specs section
* Please use dummy json to populate the table. For reference you can see the **Need Help?** section below
* You should use a modern frontend framework like **ReactJS**, **AngularJS**, **VueJS** etc to
implement this.
* It should support basic localization of strings in 2 languages. There should be a button to select
between different languages. **(Optional bonus point)**

Once you are done, please share with us:
1. Source code link (GitHub, BitBucket, etc)
2. URL where you have hosted the project

# Specs

# Need Help?

* Sample json to render the data

```javascript

{
  "data": [{
      "name": "Test Whatsapp",
      "region": "US",
      "createdOn": 1559807714999,
      "price": "Price info of Test Whatsapp",
      "csv": "Some CSV link for Whatsapp",
      "report": "Some report link for Whatsapp",
      "image_url":"Some image url of the campaign" 
    },
    {
      "name": "Super Jewels Quest",
      "region": "CA, FR",
      "createdOn": 1559806715124,
      "price": "Price info of Super Jewels Quest",
      "csv": "Some CSV link for Super Jewels Quest",
      "report": "Some report link for Super Jewels Ques",
      "image_url":"Some image url of the campaign"
    },
    {
      "name": "Mole Slayer",
      "region": "FR",
      "createdOn": 1559806711124,
      "price": "Price info of Mole Slayer",
      "csv": "Some CSV link for Mole Slayer",
      "report": "Some report link for Mole Slayer",
      "image_url":"Some image url of the campaign"
    },
    {
      "name": "Mancala Mix",
      "region": "JP",
      "createdOn": 1559806680124,
      "price": "Price info of Mancala Mix",
      "csv": "Some CSV link for Mancala Mix",
      "report": "Some report link for Mancala Mix",
      "image_url":"Some image url of the campaign"
    }
  ]
}
```
* How to create Repo in GitHub? [Click here](https://guides.github.com/activities/hello-world/) 

* How to host your WebApp online? [Click here](https://gist.github.com/TylerFisher/6127328) or [Click here](https://pages.github.com/)

