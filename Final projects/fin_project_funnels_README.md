# practicum

**Description:**
**The key purposes of the research:**

    1. Analyze the correlation between the target event — `contacts_show` — and other user actions.
    2. Evaluate which actions related to `contacts_show` are performed more often.

To investigate these points, we will identifi the most common funnels of actions that lead users to the target event and compared their mean time duration, mean event count and conversion.

During the research we also will test two hypotheses:

    1. Some users perform actions `tips_show` and `tips_click`, others — only `tips_show`. This two groups have differences in conversion to `contact_view`. 

    2.There is a certain number of searches on the site, after which the probability of conversion to the target action begins to change (fall). The main idea, that during an increase of the number of searches on the site, you can track the moment when the conversion of a group with a new number of searches will change in comparing to the previous one. You, as a product, can use this moment to interact with user to boost his or her loyalty.
    
**Data description:**

**mobile_sources.csv:**

- `userId` — user ID,
- `source` — app installation source.

**mobile_dataset.csv:**

- `event.time` — the time of the event,
- `user.id` — user ID,
- `event.name ` — user action.

**Types of actions:**

- `advert_open` — opened the advert cards,
- `photos_show` — viewed photos in the advert,
- `tips_show` — saw recommended ads,
- `tips_click` — clicked on the recommended ad,
- `contacts_show` and `show_contacts` — looked at the phone number,
- `contacts_call` — called the number from the ad,
- `map` — opened the ad map,
- `search_1`—`search_7` — various actions related to site search,
- `favorites_add` — added the ad to favorites.

**Project Stack:**
Matplotlib, Pandas, Plotly, Python, Seaborn.

****Knowledge and skills used:**
A/B testing, statistical hypothesis testing, z-test, product metrics, event analytics

**Key conclusion/result of the project:** 
In tne presentation: https://disk.yandex.ru/i/heOn-EGPXihB-w

**Project status:**
The project has been successfully completed on time.

