# Azure Open AI

> Challenge created as part of the Microsoft AI Fundamentals Bootcamp by DIO, based on the tutorials:

- [Explore generative AI in Azure AI Foundry Portal](https://aka.ms/ai900-bing-copilot)

---

## 1. Explore generative AI in Azure AI Foundry Portal

### 1.1. Create a project in Azure AI Foundry portal

- Navigate to [Azure AI Froundry](https://ai.azure.com/).

- Create a project and new hub

- After the resources are created, you will be brought to your project’s Overview page. On the left-hand menu on the screen, select *Playgrounds*.

<div align="center">
    <img src="./assets/azure-ai-foundry-playgrounds.png" title="Azure AI Froundry Playgrounds" width="40%" /> 
</div>
<div align="center">Azure AI Froundry Playgrounds</div>

### 1.2. Explore generative AI in Azure AI Foundry’s chat playground

- In Azure AI Foundry’s Playgrounds page, select **Try the Chat playground**. 

- In order to use *Chat playground*, you need to associate it with a deployed model. In the *Chat playground*, select **Create a deployment**. Search for and select **gpt-4**.

- In the *Deploy model* window, keep the default naming and selection and select **Deploy**

- In the chat playground, you can use your deployed model when it appears in the Deployment selection menu.

### 1.3. Using generative AI

Let’s try generating a resonse using a prompt with a specific goal.

**Prompt 01:**

```
I'm planning to travel to Japan in December. Can you make a checklist of everything I need to do?
```

**Output:**

```
Sure! Here's a checklist to help you prepare for your trip to Japan in December:  
   
1. Passport: Ensure your passport is valid for at least six months beyond your travel dates.  
   
2. Visa: Check if you need a tourist visa to enter Japan and apply for one if necessary.  
   
3. Flights: Book your flights to and from Japan.  
   
4. Accommodations: Reserve hotels or other accommodations for your stay.  
   
5. Travel insurance: Purchase travel insurance that covers medical expenses, trip cancellations, and lost luggage.  
   
6. Vaccinations: Consult with a healthcare provider to ensure you are up-to-date on routine vaccinations and any recommended for travel to Japan.  
   
7. Currency exchange: Exchange some money for Japanese yen or plan to withdraw cash from ATMs upon arrival.  
   
8. Transportation: Research and plan transportation options within Japan, such as trains, buses, or car rentals.  
   
9. Itinerary: Plan your itinerary, including must-see attractions, cultural experiences, and any events or festivals happening in December.  
   
10. Packing: Make a packing list that includes warm clothing, comfortable shoes, travel adaptors, and any necessary medications.  
   
11. Language: Learn some basic Japanese phrases or download a translation app to help you communicate while in Japan.  
   
12. COVID-19 guidelines: Stay updated on any travel restrictions or health guidelines related to COVID-19.  
   
13. Notify bank: Inform your bank and credit card companies about your travel dates to avoid any issues with using your cards abroad.  
   
14. Copies of important documents: Make copies of important documents like your passport, visa, and travel insurance, and keep them separate from the originals.  
   
15. Mobile phone: Check with your mobile phone provider about international roaming or consider renting a portable Wi-Fi device in Japan.  
   
By following this checklist, you can ensure a smooth and enjoyable trip to Japan in December. Safe travels!
```
<br />

---

Now, let’s iterate based on previous prompts and responses to refine the result. 

**Prompt 02:**

```
Can you give me more information about the item 7?
```

**Output:**

```
Yes! Here’s what you need to know about currency exchange in Japan:  

1. Currency Used 
Japan’s official currency is the Japanese Yen (JPY, ¥). Banknotes come in denominations of ¥1,000, ¥2,000 (rare), ¥5,000, and ¥10,000, while coins are ¥1, ¥5, ¥10, ¥50, ¥100, and ¥500.  

2. Where to Exchange Money
- Airports: You can exchange money at major airports like Narita (Tokyo), Haneda (Tokyo), and Kansai (Osaka). The rates may not be the best but are convenient.  
- Banks & Post Offices: Many banks and post offices offer currency exchange services, but they may have limited operating hours.  
- Currency Exchange Counters: You can find money exchange kiosks in popular tourist areas, such as Shinjuku, Shibuya, and Akihabara in Tokyo.  
- ATMs: ATMs at **7-Eleven, Japan Post Bank, and FamilyMart (E-net ATMs)** accept most international debit/credit cards and often offer competitive exchange rates.  

3. Best Ways to Exchange Money 
- Bring some cash in your local currency and exchange it upon arrival. 
- Use a debit/credit card with low foreign exchange fees at ATMs. Visa, Mastercard, and American Express are widely accepted, though some places may prefer cash.  
- Avoid exchanging money at hotels, as their rates are usually unfavorable.  

4. Credit Cards & Mobile Payments  
- Credit cards (Visa, Mastercard, JCB, AMEX) are widely accepted in cities but not always in rural areas.  
- Suica and Pasmo IC Cards (prepaid transit cards) can also be used for small purchases.  
- Mobile payments like Apple Pay, Google Pay, PayPay, and Line Pay are becoming more popular.  

5. Exchange Rate Tips 
- Check exchange rates before your trip using websites like XE.com or your bank’s app.  
- Avoid airport kiosks if possible, as their rates tend to be higher.  
- Consider using a multi-currency travel card** like Wise or Revolut for better exchange rates.  
```
<br />

---

To finish, let’s try to add context to maximize the relevance of the response.

**Prompt 03:**

```
 What three places do you recommend I stay in Japan to be within walking distance to historical attractions? Explain your reasoning.

```

**Output:**

```
If you're looking for places to stay in Japan that are within walking distance of historical attractions, here are my top three recommendations:  

1. Gion, Kyoto  
📍 Why Stay Here? 
Gion is Kyoto’s famous geisha district, known for its well-preserved traditional streets, temples, and tea houses. Staying here allows you to walk to some of Japan’s most iconic historical sites while soaking in the old-world charm.  

🏯 Nearby Historical Attractions (All Walkable) 
- Kiyomizu-dera Temple – A UNESCO World Heritage Site with stunning hillside views.  
- Yasaka Shrine – A beautiful Shinto shrine with vibrant festivals.  
- Kennin-ji Temple – Kyoto’s oldest Zen temple, founded in 1202.  
- Ninenzaka & Sannenzaka Streets – Historic shopping streets with Edo-period architecture.  

🛏 Where to Stay? 
- Luxury: Hoshinoya Kyoto (traditional ryokan experience)  
- Mid-range: Gion Hatanaka (close to Yasaka Shrine)  
- Budget: Guesthouse Soi (traditional Japanese-style stay)  

---

2. Asakusa, Tokyo  
📍 Why Stay Here? 
Asakusa is Tokyo’s most historic district, home to Senso-ji, Tokyo’s oldest Buddhist temple. It offers a mix of tradition and modern conveniences, with great street food, shopping, and a direct connection to other parts of Tokyo.  

🏯 Nearby Historical Attractions (All Walkable)  
- Senso-ji Temple – Tokyo’s most famous and oldest Buddhist temple.  
- Nakamise Shopping Street – A historic shopping street dating back to the Edo period.  
- Sumida Park – Perfect for cherry blossom season with views of Tokyo Skytree.  
- Edo-Tokyo Museum (short walk) – Learn about Tokyo’s transformation from Edo-era to modern times.  

🛏 Where to Stay? 
- Luxury: The Gate Hotel Asakusa Kaminarimon  
- Mid-range: Richmond Hotel Asakusa  
- Budget: K’s House Tokyo (hostel with private rooms)  

---

3. Nara Park Area, Nara
Why Stay Here? 
Nara was Japan’s first capital (710-784 AD) and is filled with ancient temples, shrines, and friendly roaming deer. Staying near Nara Park lets you experience Japan’s oldest cultural treasures without needing transportation.  

🏯 Nearby Historical Attractions (All Walkable)  
- Todai-ji Temple – Home to the Great Buddha (Daibutsu), one of Japan’s most famous landmarks.  
- Kasuga Taisha Shrine – An ancient Shinto shrine with thousands of stone lanterns.  
- Kofuku-ji Temple – A beautiful 5-story pagoda and former headquarters of the Fujiwara clan.  
- Naramachi – A preserved historic district with Edo-period merchant houses.  

🛏 Where to Stay? 
- Luxury: Nara Hotel (historic hotel, once visited by emperors and royalty)  
- Mid-range: Setre Naramachi  
- Budget: Guesthouse Nara Backpackers (traditional Machiya house)  

---

Final Thoughts  
- If you love traditional tea houses and geisha culture, stay in Gion, Kyoto.  
- If you want a mix of city life and history, stay in Asakusa, Tokyo.  
- If you prefer a peaceful, nature-filled atmosphere with ancient temples, stay in 
Nara Park, Nara.  
```