Q1. Festival Ticket Analysis: Custom Selection

You are a data professional working for TicketPlus Inc., a global ticketing platform for festivals. TicketPlus wants to analyze its operational performance, attendee behavior, and festival profitability across the world. Using the provided dataset, you are tasked with answering specific business questions that cover diverse SQL concepts. These insights will help optimize sales strategies, improve customer satisfaction, and increase revenue.

Your SQL expertise is required to solve the case study
Write a SQL Query to retrieve the Festival_Name, Country, and Ticket_Type for all festivals.

**Schema	festivaldata**
Columns	
Festival_ID (INT)	Unique identifier for each festival.
Festival_Name (VARCHAR)	Name of the festival.
Country (VARCHAR)	Country where the festival is held.
City (VARCHAR)	City where the festival is held.
Date (DATE)	Date of the festival.
Ticket_Type (VARCHAR)	Type of ticket sold (e.g., "Regular", "VIP").
Price (DECIMAL)	Price of a ticket in USD.
Attendee_ID (INT)	Unique identifier for each attendee.
Attendee_Age (INT)	Age of the attendee.
Gender (CHAR)	Gender of the attendee (e.g., "M" for Male, "F" for Female).
Purchased_On (DATE)	Date the ticket was purchased.
Payment_Method (VARCHAR)	Payment method used (e.g., "Credit Card", "PayPal").
Discount_Code (VARCHAR)	Discount code applied during purchase, if any.
Feedback_Rating (INT)	Rating given by the attendee (scale: 1-5).
Organizer_Profit (DECIMAL)	Profit made by the festival organizer in USD.

Festival_ID	Festival_Name	Country	City	Date	Ticket_Type	Price	Attendee_ID	Attendee_Age	Gender	Purchased_On	Payment_Method	Discount_Code	Feedback_Rating	Organizer_Profit
101	Holi Festival	India	Delhi	2024-03-15T00:00:00.000Z	Regular	50	1	25	F	2024-02-20T00:00:00.000Z	Credit Card	FEST10	5	20000
102	Coachella	USA	Indio	2024-04-10T00:00:00.000Z	VIP	400	2	30	M	2024-03-15T00:00:00.000Z	PayPal	VIP50	4	1200000
103	Oktoberfest	Germany	Munich	2024-09-25T00:00:00.000Z	Regular	100	3	35	M	2024-08-10T00:00:00.000Z	Debit Card	null	4	500000
104	Sunburn Festival	India	Goa	2024-12-28T00:00:00.000Z	VIP	150	4	28	F	2024-11-30T00:00:00.000Z	Credit Card	FEST20	3	70000
105	Tomorrowland	Belgium	Boom	2024-07-20T00:00:00.000Z	Regular	350	5	29	M	2024-06-15T00:00:00.000Z	Bank Transfer	EARLY30	5	2000000
106	Durga Puja	India	Kolkata	2024-10-10T00:00:00.000Z	Regular	20	6	40	F	2024-09-30T00:00:00.000Z	UPI	null	4	5000
107	Rio Carnival	Brazil	Rio	2024-02-20T00:00:00.000Z	VIP	300	7	34	F	2024-01-15T00:00:00.000Z	Credit Card	null	5	400000
108	Edinburgh Fringe	UK	Edinburgh	2024-08-15T00:00:00.000Z	Regular	75	8	27	M	2024-07-10T00:00:00.000Z	PayPal	null	3	250000
109	Diwali Celebration	India	Jaipur	2024-11-04T00:00:00.000Z	VIP	100	9	32	F	2024-10-15T00:00:00.000Z	UPI	DIWALI15	5	30000
110	Sundance Film Festival	USA	Utah	2024-01-20T00:00:00.000Z	Regular	120	10	45	M	2023-12-25T00:00:00.000Z	Credit Card	EARLYBIRD	4	150000


