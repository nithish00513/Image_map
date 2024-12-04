# Ex04 Places Around Me
# Date:
# AIM
To develop a website to display details about the places around my house.

# DESIGN STEPS
## STEP 1
Create a Django admin interface.

## STEP 2
Download your city map from Google.

## STEP 3
Using <map> tag name the map.

## STEP 4
Create clickable regions in the image using <area> tag.

## STEP 5
Write HTML programs for all the regions identified.

## STEP 6
Execute the programs and publish them.

# CODE
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>ImageMap</title>
</head>
<body>
    <img src="map.png" alt="map image" usemap="#map">
    <map name="#map">
        <area shape="poly" coords="157,13,170,7,207,3,257,7,287,29,283,57,247,45,183,49,163,31" href="chennai.html" alt="chennai">
        <area shape="poly" coords="112,147,128,147,164,147,189,146,223,144,252,145,267,155,267,177,219,179,237,183,185,176,151,182,126,182,108,172,107,156" href="pudhucherry.html" alt="pudhucherry">
        <area shape="poly" coords="44,273,31,283,27,301,33,306,43,317,57,317,83,319,113,319,133,314,138,298,118,279,82,270" href="thanjavur.html" alt="thanjavur">
        <area shape="poly" coords="21,42,32,20,51,19,72,17,104,31,116,55,93,63,69,61,39,59" href="vellore.html" alt="vellore">
        <area shape="poly" coords="29,110,52,104,84,106,123,103,146,100,175,105,164,132,127,137,93,138,58,140,28,135,20,124,39,141" href="thiruvannamalai.html" alt="tvm">
    </map>
</body>
</html>
```
chennai.html
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>chennai</title>
</head>
<body>
    <center><h1>CHENNAI</h1></center>
    <center><img src="chennai.jpg" alt="chennai Imagep" style="width: 800px;"></center>
    <p>Chennai formerly known as Madras, is the capital city of Tamil Nadu, the southernmost state of India. It is the state's primate city and is located on the Coromandel Coast of the Bay of Bengal. According to the 2011 Indian census, Chennai is the sixth-most populous city in India and forms the fourth-most populous urban agglomeration. Incorporated in 1688, the Greater Chennai Corporation is the oldest municipal corporation in India and the second oldest in the world after London.

        Historically, the region was part of the Chola, Pandya, Pallava and Vijayanagara kingdoms during various eras. The coastal land which then contained the fishing village Madrasapattinam, was purchased by the British East India Company from the Nayak ruler Chennapa Nayaka in the 17th century. The British garrison established the Madras city and port and built Fort St. George, the first British fortress in India. The city was made the winter capital of the Madras Presidency, a colonial province of the British Raj in the Indian subcontinent. After India gained independence in 1947, Madras continued as the capital city of the Madras State and present-day Tamil Nadu. The city was officially renamed as Chennai in 1996.
        
        The city is coterminous with Chennai district, which together with the adjoining suburbs constitutes the Chennai Metropolitan Area,[c] the 35th-largest urban area in the world by population and one of the largest metropolitan economies of India. Chennai has the fifth-largest urban economy and the third-largest expatriate population in India. As a gateway to South India, Chennai is among the most-visited Indian cities ranking 36th among the most-visited cities in the world in 2019. Ranked as a beta-level city in the Global Cities Index, Chennai regularly features among the best cities to live in India and is amongst the safest cities in India.
        
        Chennai is a major centre for medical tourism and is termed "India's health capital". Chennai houses a major portion of India's automobile industry, hence the name "Detroit of India". It was the only South Asian city to be ranked among National Geographic's "Top 10 food cities" in 2015 and ranked ninth on Lonely Planet's best cosmopolitan cities in the world. In October 2017, Chennai was added to the UNESCO Creative Cities Network (UCCN) list. It is a major film production centre and home to the Tamil-language film industry.</p>
</body>
</html>
```
vellore.html
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Vellore</title>
</head>
<body>
    <center><h1>VELLORE</h1></center>
    <center><img src="vellore.jpg" alt="vellore image" style="width: 1000px;"></center>
    <p>Vellore (English: VAY-loor), also natively spelt as Velur,[note 1] is a sprawling city and the administrative headquarters of Vellore district in the Indian state of Tamil Nadu. It is located on the banks of the Palar River in the northeastern part of Tamil Nadu and is separated into four zones that are further subdivided into 60 wards, covering an area of 76.09  km2 and housing a population of 315128 as reported by the 2011 census.[4] It is located about 137.20 kilometres (85 mi) west of Chennai, and about 213.20 kilometres (132 mi) east of Bangalore. Vellore is located on the Mumbai–Chennai arm of the Golden Quadrilateral. Vellore is governed under a mayor and the Vellore Municipal Corporation. It is a part of both the Lok Sabha and state assembly constituencies of Vellore.

        Vellore is the home to Christian Medical College & Hospital,[5] the Vellore Institute of Technology (VIT)[6] and Sripuram Golden Temple.
        
        The Vellore region is the largest exporter of finished leather goods in the country. Leather exports from Vellore account for more than 37% of India's leather exports and leather-related products.[7]
        
        Vellore is one of 27 cities chosen by the Government of India to take part in the country's Smart Cities Mission.
        
        Oxford Economics Global Cities Index 2024 ranked Vellore as 24th Best City in India and 729 th best city in the world [8]The recorded history of Vellore dates back to the ninth century, as seen from a Chola inscription in the Annamalaiyar Temple in Tiruvannamalai.[10]

        Vellore is strategically located and well-connected by rail and bus routes to major towns in the neighbouring states of Andhra Pradesh, Karnataka and Kerala. Many dynasties and rulers dominated Vellore throughout its history, including the Pallava dynasty, Medieval Cholas, Later Cholas, the Rashtrakuta dynasty, the Sambuvaraya chieftains, Vijayanagar, the Nawabs of the Carnatic, and the administration of the British. In the 18th century, Vellore was involved in the Carnatic Wars between Britain and France. It was situated close to several decisive battles, including those at Ambur (1749), Arcot (1751), and Vandavasi (1760).
        
        
        Thomas Daniell (1749-1840)- The Fort of Vellore in the Carnatic, India
        Vellore Fort is important to Vellore's history. Due to a lack of historical records, it is not known exactly when the fort was constructed, but estimates based on stone inscriptions suggests that the fort was most likely built during the rule of Chinna Bommi Nayak between 1526 and 1595. The fort is a good example of Tamil Nadu military architecture, while the Jalakandeswarar Temple within the fort represents Vijayanagara architecture.
        
        Christian Medical College & Hospital, founded in 1900 by the American medical missionary Dr. Ida S. Scudder, is another Vellore landmark. The hospital has grown into a medical institution of international repute.[11][12]
        
        The central prison in Vellore, established in 1830, had imprisoned notable figures like C. Rajagopalachari and Ramaswamy Venkataraman. Other landmarks include the Aruganthampoodi mausoleums, located close to the section of National Highway 48 between Vellore and Arcot, where the family members of Tipu Sultan were buried; and the Muthu Mandapam, a memorial on the banks of Palar River built by the Tamil Nadu Government to honor Sri Vikrama Rajasinha, the last ruler of the Kingdom of Kandy in Sri Lanka, who ruled from 1798 to 1815 and was imprisoned in Vellore Fort for 17 years until his death.</p>
</body>
</html>
```
thiruvannamalai.html
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Thiruvannamalai</title>
</head>
<body>
    <center><h1>THIRUVANNAMALAI</h1></center>
    <CEnter><img src="Thiruvannamalai.jpg" alt="thiruvannamalai Image" style="width: 800px;"></CEnter>
    <p>Tiruvannamalai (Tamil: Tiruvaṇṇāmalai IPA: ˈtiɾɯʋaɳːaːmalɛi̯, otherwise spelt Thiruvannamalai; Trinomali or Trinomalee[3] on British records) is a city, a spiritual, cultural, economic hub and also the administrative headquarters of Tiruvannamalai District in the Indian state of Tamil Nadu. The city is home to the renowned Annamalaiyar temple, Annamalai hill, Girivalam and the Karthigai Deepam festival and a prominent pilgrimage destination.[4]

        Tiruvannamalai has a thriving service sector industry, including retail, resorts and recreation activities. Apart from the service sector, the city is also the hub for many industrial setups including SIDCO,[5][6] spinning mills and premier educational institutions.[7][8] The city is administered by the Tiruvanamalai City Municipal Corporation, originally constituted in the year 1886 as Tiruvannamalai Municipality.[9] The city has a good network of roadways and railways connecting it with Chennai (150 km) and Bengaluru (145 km). The Union Ministry of Civil Aviation is considering setting up a new airport at Tiruvannamalai.[10]In Hinduism, Parvati, wife of Shiva, once closed the eyes of her husband playfully in a flower garden at their abode atop Mount Kailash. Although only a moment for the gods, all light was taken from the universe, and the earth, in turn, was submerged in darkness for years. Parvati performed penance with other devotees of Shiva, and her husband appeared as a big column of fire at the top of Annamalai hills, returning light to the world.[11] He then merged with Parvati to form Ardhanarishvara, the half-female, half-male form of Shiva.[12] The Annamalai, or red mountain, lies behind the Annamalaiyar temple, and is associated with the temple of its namesake.[13] The hill is sacred and considered a lingam, or iconic representation of Shiva, in itself.[14] Another legend is that once, while Vishnu and Brahma contested for superiority, Shiva appeared as a flame, and challenged them to find his source.[15][16] Brahma took the form of a swan, and flew to the sky to see the top of the flame, while Vishnu became the boar Varaha, and sought its base. The scene is called lingothbava, and is represented in the western wall at the sanctum of most Shiva temples. Neither Brahma nor Vishnu could find the source, and while Vishnu conceded his defeat, Brahma lied and said he had found the pinnacle. In punishment, Shiva ordained that Brahma would never have temples on earth in his worship.[15] In Tamil, the word Arunam means red or fire and Asalam means hill. Since Shiva manifested himself in the form of fire in this place, this name Arunachalam came to be associated with Annamalai hill and the city.[16] The first mention of Annamalai is found in Tevaram, the seventh century Tamil Saiva canonical work by Appar and Tirugnanasambandar.[17]</p>
</body>
</html>
```
pudhucherry.html
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Pudhucherry</title>
</head>
<body>
    <center><h1>PUDHUCHERRY</h1></center>
    <center><img src="pudhucherry.jpg" alt="pudhucherry Image" style="width: 1000px;"></center>
    <p>Puducherry, formerly known as Pondicherry, gained its significance as "the French Riviera of the East" after the advent of French colonialisation in India. Puducherry is the Tamil interpretation of "new town" and mainly derives from "Poduke", the name of the marketplace or "port town" for Roman trade in the 1st century, as mentioned in the Periplus of the Erythraean Sea. The settlement was once an abode of learned scholars versed in the Vedas, hence it was also known as Vedapuri.[3]

        The history of Puducherry can broadly be classified into two periods: pre-colonial and colonial. The pre-colonial period started with the reign of the Pallavas, who ruled the empire from 325 to 900, after which came the Chola dynasty, from 900 to 1279, and the Pandya dynasty, from 1279 to 1370. During the 14th century, the city was under the rule of Naikship of Gingee of the Vijayanagara Empire, from 1370 to 1614, when it was conquered by the Sultan of Bijapur, who ruled it from 1614 to 1638. It was during this period that Portuguese and Danish merchants used it as a trading center.
        
        The colonial period began with the Portuguese, the first Europeans to conduct trade in textiles, in 1521, and subsequently, the Dutch and the Danes in the 17th century.
        
        The prospering trade of Puducherry attracted the French, and the predominant feature of the town was laid by the French pioneer Francois Martin in the form of a French settlement, in 1674. In 1693, Puducherry was captured by the Dutch and subsequently restored in 1699, with the Treaty of Ryswick.
        
        The French acquired Mahé in 1720, Yanam in 1731, and Karaikal in 1738. The British captured the city from the French but returned it following the Treaty of Paris, in 1763. This Anglo-French war continued until 1814, where France found itself in control of the settlements of Puducherry, Mahé, Yanam, Karaikal, and Chandernagor, even during the British period, until 1954. It was a reign of 138 years under the French, who on 31 October 1954 left Indian shores following a de facto transfer of power.
        
        Nearby places such as Arikamedu, Ariyankuppam, Kakayanthoppe, Villianur, and Bahour, which were colonised by the French East India Company over a period of time and later became the union territory of Pondicherry, have recorded histories that predate the colonial period.
        
        Poduke or Poduca (marketplace) was a Roman trading destination from the third century BCE.[4] Poduca has been identified as possibly being Arikamedu (now part of Ariyankuppam), located about 2 miles (3.2 km) from the modern city of Pondicherry. The area was part of the Pallava Kingdom of Kanchipuram in the 4th century. The Cholas of Thanjavur held it from the 10th to the 13th centuries, until it was replaced by the Pandya Kingdom, in the 13th century. The Vijayanagar Empire took control of almost all of southern India in the 14th century and maintained control until 1638, when they were supplanted by the Sultan of Bijapur.
        
        In 1674, the French East India Company set up a trading centre at Pondicherry, and this outpost eventually became the chief French settlement in India. The French governor François Martin made remarkable improvements to the city and its commercial ties, facing at the same time strong opposition from the Dutch and the English. He entered into extended negotiations with the sultans of Golconda through the intercession of several roving French merchants and doctors who were in favour with the sultan. Trading in jewellery and precious stones, which had become highly fashionable in European courts, was one among many activities. Five trading posts were established along the south Indian coast between 1668 and 1674. The city was separated by a canal into the French Quarter and the Indian Quarter.[5]
        
        On 21 August 1693, during the Nine Years' War, Pondicherry was captured by the Dutch. The governor of Dutch Coromandel, Laurens Pit the Younger, sailed with a fleet of seventeen ships and 1,600 men from Nagapattinam and bombarded Pondicherry for two weeks, after which Francois Martin surrendered it. At the Peace of Ryswick, it was agreed by all parties to return conquered territories, and in 1699, Pondicherry was handed back to the French.[6]
        
        On 16 January 1761, the British captured Pondicherry from the French, but it was returned under the 1763 Treaty of Paris, at the conclusion of the Seven Years' War.[7] The British took control of the area again in 1793, at the Siege of Pondicherry, amid the Wars of the French Revolution, and returned it to France in 1814.
        
        
        Prime Minister Nehru visiting Pondicherry a few months after the de facto transfer
        On 18 March 1954, a number of resolutions were passed by the municipalities in Pondicherry, demanding an immediate merger with India. Some days later, similar resolutions were passed by the municipalities in Karaikal. The resolutions had the full support of the French Indian Councillors, popularly known as ministers, and the president of the representative assembly. These municipalities represented roughly 90% of the population of the French possessions, and they called upon the government of France to take urgent and necessary measures to give effect to the wishes of the people.[8] The government of India had made it clear that the cultural and other rights of the people would be fully respected. They were not asking for the immediate transfer of de jure sovereignty of France. Their suggestion was that a de facto transfer of the administration should take place immediately, while French sovereignty should continue until the constitutional issue had been settled. Both India and France would have to make necessary changes in their respective constitutions. All this would take time, while the demand of the people was for an immediate merger without a referendum. The government of India was convinced that the suggestion which they made would help to promote a settlement, which they greatly desired.[8]
        
        On 18 October 1954, in a general election involving 178 people in municipal Pondicherry and the Commune of Panchayat, 170 people were in favour of the merger, and eight people voted against. The de facto transfer of the French Indian territories from French governance to the Indian union took place on 1 November 1954 and was established as the union territory of Pondicherry. The treaty effecting the de jure transfer was signed in 1956. However, due to opposition in France, the ratification of this treaty by the French National Assembly only took place on 16 August 1962.</p>
</body>
</html>
```
thanjavur.html
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Thanjavur</title>
</head>
<body>
    <center><h1>THANJAVUR</h1></center>
    <center><img src="thanjavur.jpg" alt="thanjavur Image" style="width: 800px;"></center>
    <p>Thanjavur (Tamil: [t̪aɲdʑaːʋuːɾ]), also known as Thanjai, previously known as Tanjore,[1] is a city in the Indian state of Tamil Nadu. It is the 12th biggest city in Tamil Nadu. Thanjavur is an important center of southern Indian religion, art, and architecture. Most of the Great Living Chola Temples, which are UNESCO World Heritage Monuments, are located in and around Thanjavur. The foremost among these, the Brihadeeswara Temple, built by the Chola emperor Rajaraja I, is located in the centre of the city. This temple has one of the largest bull statues (called Nandi[2]) in India carved out of a single granite rock. Thanjavur is also home to Tanjore painting, a painting style unique to the region. Thanjavur is the headquarters of the Thanjavur District. The city is an important agricultural centre located in the Kaveri Delta and is known as the Rice bowl of Tamil Nadu. Thanjavur is administered by a municipal corporation covering an area of 36.31 km2 (14.02 sq mi) and had a population of 222,943.[3] Roadways are the major means of transportation, while the city also has rail connectivity. The nearest airport is Tiruchirapalli International Airport, located 59.6 km (37.0 mi) away from the city. The nearest seaport is Karaikal, which is 94 km (58 mi) away from Thanjavur. The city first rose to prominence during the reign of the Cholas when it served as the capital of the empire. After the fall of the Cholas, the city was ruled by various dynasties such as the Mutharaiyar dynasty, the Pandyas, the Vijayanagar Empire, the Madurai Nayaks, the Thanjavur Nayaks, the Thanjavur Marathas and the British Empire. It has been a part of independent India since 1947.</p>
</body>
</html>
```



# OUTPUT
![Screenshot 2024-11-28 143130](https://github.com/user-attachments/assets/bfdd3ba4-2f27-44df-b48b-0ec0e566529c)
![image](https://github.com/user-attachments/assets/99be0390-06ba-45fa-8c40-ad9cd0fb7cb6)
![Screenshot 2024-11-28 143517](https://github.com/user-attachments/assets/26f0e0c8-4a89-4dfd-8051-53d2de86c82a)
![Screenshot 2024-11-28 143831](https://github.com/user-attachments/assets/1e47c92e-7703-4857-a76e-90df35e183b8)
![Screenshot 2024-11-28 144228](https://github.com/user-attachments/assets/c44e375e-cde7-463c-9e70-a7a6f7cd4ff4)
![Screenshot 2024-11-28 144409](https://github.com/user-attachments/assets/d0f8e4d0-2f96-4b8f-8ae5-a0e6e04b1112)

# RESULT
The program for implementing image maps using HTML is executed successfully.
