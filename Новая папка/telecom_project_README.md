# practicum
AB project description.

**Description:**

You are an analyst at Megaline, a federal mobile operator. You will have to make a analysis of tariffs on a small sample of customers. You have the data of 500 Megalyne users. It is necessary to analyze the behavior of customers and conclude which tariff is better.

**Data description:**

Users table (information about users):
    user_id — unique user ID
    first_name — user name
    last_name — last name of the user
    age — user's age (years)
    reg_date — date of tariff activation (day, month, year)
churn_date — date of termination of tariff use (if the value is omitted, the tariff was still valid at the time of data upload)
city — the user's city of residence
    tariff — name of the tariff plan

Calls table (information about calls):
    id — unique call number
    call_date — date of the call
    duration — the duration of the call in minutes
    user_id — ID of the user who made the call

Messages table (information about messages):
    id — unique message number
message_date — date of the message
    user_id — ID of the user who sent the message

Internet table (information about internet sessions):
    id — unique session number
    mb_used — the amount of Internet traffic spent per session (in megabytes)
session_date — the date of the Internet session
    user_id — user ID

Tariffs table (information about tariffs):
    tariff_name — name of the tariff
    rub_monthly_fee — monthly subscription fee in rubles
    minutes_included — the number of minutes of conversation per month included in the subscription fee
    messages_included — the number of messages per month included in the subscription fee
    mb_per_month_included — the amount of Internet traffic included in the subscription fee (in megabytes)
rub_per_minute - the cost of a minute of conversation over the tariff package 
rub_per_message — the cost of sending a message over the tariff package
    rub_per_gb — the cost of an additional gigabyte of Internet traffic over the tariff package 

**Project Stack:**
Matplotlib, NumPy, Pandas, Python,SciPy

**Knowledge and skills used:**
descriptive statistics, statistical hypothesis testing

**Key conclusion/result of the project:**
We were found differences in the behavior of users of the two tariffs provided. For example, users of the "ultra" tariff rarely pronounce a package of minutes for telephone conversations, and the SMS limit indicated by the tariff is not used in any of the tariffs. The more expensive "ultra" tariff brings more revenue to the company. Users of Moscow and other regions do not significantly differ in terms of revenue. Therefore, it does not make sense to promote the tariff within the capital in particular.

**Project status:**
The project has been completed and successfully completed on time.
