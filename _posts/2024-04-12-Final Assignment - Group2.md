<H1> Risk Assessment for Pampered Pets </H1>
<H2>Authors: Brandon Pang, Abdallah Hamad and Sudesh Naidoo	</H2>											
 


<H2>Introduction</H2>

<p>Pampered pets are a bricks-and-mortar business which we are assessing to be transformed into a digital, world-class online business. </p> 
<H2>Scope and Assessment Approach </H2>
<p></p>This report focuses mainly on the cyber security requirements that a basic online system should have in place including an overview SWOT analysis.  This assessment will include any known risks identified by using the STRIDE and Attack tree methodologies, which highlights security vulnerabilities of digital implementations. 
We propose all systems and applications be cloud based and a well-known cloud service provider (CSP) such as Amazon Azure be used. Firewalls, virus protection, backup and virus protection are usually standard. A well-known CSP should be ISO27001 certified.</p>

<H2>Current risks</H2>
The below Attack tree shows that currently the systems used are at risk and required at minimum, access control, antivirus, data storage encryption, use of outdated software (may not support security patch updates).

Diagram 1 (VisualParadigm. n.d.)
![image](https://sudesh74.github.io/assets/images/banners/cyber1.jpg) 
![assignmentfile](https://sudesh74.github.io/assets/images/banners/FinalAssignment1-Group2.pdf)


SWOT analysis


<H3>STRENGTHS</H3>
<p>⦁	Strong Local Supply Chain Relationships.
⦁	Existing Digital Tools for Operations.
⦁	Dedicated and Knowledgeable Staff.

<H3>WEAKNESSES</H3>
⦁	Limited Digital Presence.
⦁	Dependency on Local Suppliers.
⦁	Lack of Online Marketing Experience.
⦁	Vulnerability to Market Shifts.
<H3>OPPORTUNITIES</H3>
⦁	Digital Market Expansion.
⦁	Product Diversification.
⦁	Collaborations and Partnerships.
<H3>THREATS</H3>
⦁	Competitive Disadvantage.
⦁	Cybersecurity Risks.
⦁	Changing Consumer Expectations.
If Pampered Pets decides against establishing an online store or presence, it could miss several business opportunities. This could impact the company's growth, customer reach, and competitiveness. Here are key areas that could be affected: </p>
<H3>1. Limited Market Reach </H3>
<p></p>Geographic and demographic limitations: Pampered Pets is currently limiting its market by not having an online presence. It is missing out on potential sales from non-local customers interested in high-quality pet food products. Additionally, this limited reach prevents the company from tapping into younger demographics (Jain, Malviya, Arya, 2021).</p>

 
<H3>2. Decreased Sales Growth </H3>
<p>Reduced Sales Opportunities: E-commerce has been consistently growing, and many consumers prefer the convenience of shopping online. Not participating in this trend can result in lost sales opportunities and decreased revenue potential.
Limited Scalability: The business's growth is inherently limited to the number of customers who can physically visit the store, restricting scalability and the ability to expand the customer base rapidly (Wang, 2023).</p>
<H3>3. Competitive Disadvantage </H3>
<p>Increased Competition: Competitors with an online presence can capture a larger market share, including Pampered Pets’ potential customers, by offering similar products online with the convenience of home delivery.
Lagging Trends: Businesses without an online presence may fall behind as consumers increasingly favor online shopping (Ratchford, Soysal,  Zentner, Gauri, 2022).</p>
<H3>4. Customer Engagement and Loyalty </H3>
<p></p>Slower Response to Market Changes: Adapting quickly to market changes is crucial in today's fast-paced economy. Online channels provide a rapid feedback loop, enabling businesses to respond swiftly to market trends and customer needs (Roy, Singh,  Sadeque, Harrigan,  Coussement, 2023).</p>











<H2>Risk Assessment</H2>
<p>Table A below columns represents STRIDE’s methodology, the possible attack vector and the mitigating controls. Each X equates to numeral 1 and that column control is required.
Likelihood is calculated by adding all the X’s in the row. Impact is the Likelihood multiplied by 12. Twelve is the total number of controls listed on the table. More controls = higher likelihood.

STRIDE	Attack vector	HTTPS(TLS)	CSP	Access Control	Back -up	GDPR	DB Encryption	Firewall	Staff training	Digital certificates	Complex password	2FA	PC Hardening	Likelihood	Impact (Likelihood *12)
Spoofing identity	Applications (ERP, websites)	X	X	X	X	X	X	X	X		X		X	10	120
Tampering	Data quality			X	X	X	X		X		X		X	8	96
Repudiation	email	X	X			X		X	X	X				6	72
Information disclosure	Staff/ HackerPhishing	X	X	X	X	X	X	X	X		X	X	X	11	132
Denial of service	PC			X	X			X			X		X	6	72
Elevation of privileges	Hacker /Malware	X	X	X			X	X	X		X	X	X	9	108
Table A
This shows that the highest risk to mitigate is information disclosure and the attack vector would be either internal staff or external hackers. Therefore, the likelihood is the highest at 11 and impact at 120, as most controls are required for mitigation.
Table B represents Risk vs Impact (Haber, M. 2017).   The likelihood was grouped to adhere to the 12 controls and qualitative groupings. This helps breakdown the risks into colours that represent the severity should any of the attacks occur.</p>





<p>Table B (Haber, M. 2016)
Table A		Negligible

12 to 36	Minor 

48 to 72	Moderate

84 to 96	Significant

108 to 120	Severe

132 to 144
11-12	Very likely	Low Medium	Medium	Medium High	High	High
9-10	LIkely	Low	Low Medium	Medium	Medium high	High
7-8	Possible	Low	Low Medium	Medium	Medium high	Medium High
4-6	Unlikely	Low	Low Medium	Low Medium
	Medium	Medium High
1-3	Very likely	Low	Low	Low Medium
	Medium	Medium
						

Below represents an Attack tree using the STRIDE methodology.
⦁	Rectangle with rounded edges are STRIDE headings
⦁	Parallelograms represent systems/ application that can be attacked
⦁	Circles represent mitigating controls for the STRIDE risks.</p>

<p>Diagram 2 (VisualParadigm. n.d.)</p>
 


<H3>Supply Chain - positive effects of adopting an international supply chain. </H3>

<p>For the sanctity of intellectual honesty, it seems important to be upfront about an
intimidating fact: the utilization of an international supply chain comes with inherent risk.
There is the recent and obvious case of the COVID-19 global pandemic, in which
disruptions to the supply chain devastated business operations across the world
(Alessandria, 2023). However, beyond the unique benefits that will be explained further
below, there has been a great deal of learning in the aftermath of the pandemic that has
led experts to believe that there is inherent resiliency to international supply chains even
after disaster (R. S., 2023) and that there are new practices that can mitigate future
disruptions similar to Covid (Ivanov and Dolgui, 2021).
That being said, there are three main reasons why buying internationally benefits
retailers (according to Ganesan et al): global sourcing, multichannel routes to market,
and relationship-based innovation. For Pampered Pets, it is the first two benefits that
matter most. Global sourcing means that there is resiliency in product availability; a
popular dog toy that can be purchased for retail from ten different production centers
can be sold when any of those centers go down. This allows for uninterrupted service
for customers of Pampered Pets. Multichannel routes to market is a big more difficult to
understand but is just as important. If there is a new class of product, such as an
assisted throwing device for fetch, it may not catch on in popularity among customers of
the store. By being able to cycle out that product for a competing one sourced
elsewhere, Pampered Pets can try again to create traction for fetch devices with
customers. When the class of product starts to sell organically, the store can bring back
multiple competing brands again to saturate their sales. This is not possible if they
source a new product class locally as there may be only a single brand within the space
(Ganesan et al, 2009).</p>

<H3>Positive effects of moving retail online</H3>

<p>One of the most interesting aspects of the fact that an online presence is that it will
affect the business in many ways. While the obvious effect is that an internet store will
grow sales in an observably significant amount (Pozzi, 2013), it will also prevent the
loss of customers that will come from competitors moving online (McClatchey, Cattle,
and Michell, 2007). This is important because while Pozzi’s research concluded that the
web sales will not cannibalize the in-person sales, other online stores will destroy
potential sales in a material way.
An e-shop is also important because while it increases sales within a category, it also
attracts new sales that would not happen offline (Rajamma, Pasha, and Ganesh, 2007).
This is partially because one of the most important parts of an e-shop is it serves
customers that would not exist in a brick-and-mortar store. Internet shops are able to
market in non-traditional ways to non-traditional customers (Hart et al, 2000) and are
also able to serve converted customers that are in markets that do not overlap with the
original storefront (Cater, Marinsek, Cerenak, Devic, and Runov, 2018).
Because of these multiple advantages afforded by a web store, it’s extremely important
for a retail operation to move online.</p>








<H2>References:</H2>
<p>Alessandria, G. A. et al. (2023) The Aggregate Effects of Global and Local Supply
Chain Disruptions: 2020-2022. Cambridge, Mass: National Bureau of Economic
Research.
Čater, B., Marinšek, D., Čerenak, L., Devič, S. and Runov, K., 2018. Brick-and-mortar vs
online retail. book: Shaping the future: opportunities and challenges of ecommerce.
Ljubljana: Časnik Finance.
Dr. R. S. (2023) Covid19 Pandemic Related Supply Chain Disruptions, Economic
Impact and Recovery. International Journal For Multidisciplinary Research. [Online] 5
(1), .

Ganesan, S. et al. (2009) Supply Chain Management and Retailer Performance:
Emerging Trends, Issues, and Implications for Research and Practice. Journal of
retailing. [Online] 85 (1), 84–94.
Haber, M. (2017, July 6). What is Cyber Threat Intelligence? | BeyondTrust. BeyondTrust. https://www.beyondtrust.com/blog/entry/what-is-cyberthreat-intelligence
Hart, C. et al. (2000) Retailer adoption of the Internet - Implications for retail
marketing. European journal of marketing. [Online] 34 (8), 954–974.
Ivanov, D. &amp; Dolgui, A. (2021) OR-methods for coping with the ripple effect in supply
chains during COVID-19 pandemic: Managerial insights and research implications.
International journal of production economics. [Online] 232107921–107921.
Jain, V., Malviya, B. & Arya, S. (2021) An Overview of Electronic Commerce (e-Commerce). Available at: https://www.researchgate.net/publication/351775073_An_Overview_of_Electronic_Commerce_e-Commerce
[Accessed 8 March 2024]
McClatchey, J., Cattell, K. and Michell, K., 2007. The impact of online retail grocery
shopping on retail space: a Cape Town case study. Facilities, 25(3/4), pp.115-126.
P, Gourav. (2018). Risk assessment of overdue training and general training practices. LinkedIn: Log In or Sign Up. https://www.linkedin.com/pulse/risk-assessment-overdue-training-general-practices-gourav-pandey
Pozzi, A. (2013) The effect of Internet distribution on brick-and-mortar sales. The Rand
journal of economics. [Online] 44 (3), 569–583.
 Ratchford B., Soysal B., Zentner A. & Gauri D.  (2022) Online and offline retailing: What we know and directions for future research. Available at: https://www.sciencedirect.com/science/article/pii/S0022435922000070#sec0004
[Accessed 9 March 2024]
RAforMuscians. (n.d.). Risk Assessment for musicians: Templates and advice for RA / RAMS. Last Minute Musicians Blog. https://www.lastminutemusicians.com/blog/risk-assessment-musicians/
Rajamma, R.K., Paswan, A.K. and Ganesh, G., 2007. Services purchased at brick and
mortar versus online stores, and shopping motivation. Journal of Services
Marketing, 21(3), pp.200-212.
 Roy, S., Singh, G., Sadeque, S., Harrigan, P. & Coussement, K. (2023) Customer engagement with digitalized interactive platforms in retailing. Available at: https://www.sciencedirect.com/science/article/pii/S0148296323003594#s0020 [Accessed 9 March 2024]

VisualParadigm. (n.d.). Free Threat Modeling Tool. Visual Paradigm - Online Productivity Suite. https://online.visual-paradigm.com/diagrams/features/threat-modeling-tool/
 
Wang T. (2023) Research on the Impact of E‐commerce on Offline Retail. Available at: https://drpress.org/ojs/index.php/fbem/article/view/10237 
[Accessed 6 March 2024] </p>
