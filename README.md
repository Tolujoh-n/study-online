Help me to build a fully functional, highly professional, responsive and completed web application with react and tailwind (for frontend), NodeJS express and mongoDB for backend development. And integrated all the backend APIs appropriately on the frontend. 
The name of the project I wanna build is BitcoinWorld which is to be a prediction marketplace exacly as polymarket. 
Here are the description of the webApp:
1. I wanna have a Navigation bar (like 2 rows) the first row should have (logo, title, search bar, Login, signup button and light-dark mode icon(the light and dark mode must be working and default to light mode)) at the second row I wanna have the filters on the platform (Politics, Trending, Middle East, Sports, Crypto, Tech, Culture, World, Economy, Elections, Mentions) below I will describe how each filter UI  should be:


A.Politics: Inside politics component I wanna have a filter to filter the politics data by Sub-categories so before the list of cards I wanna have 1 row with this filtering options(Search bar, filter icon, save icon, after the save icon list all this sub-category(All, Trump-Putin, Trump Presidency, Trade War, Israel Ukraine, Inflation, AI Geopolitics GPT-5, Texas, Redistricting, Epstein, Jerome, Powell, Earn 4%, Fed Rates) Let have a right side pagnation at the right and  left side pagnation at the left when needed when the row is getting much. Then I wanna have the cards (4 card in a row). Inside each card should have(Topic image, title (truncate if too long), at the left and at the right wanna have a progress bar like a protractor/caliper diameter displaying the progress percentage. under this logo, title and progress I wanna have the option list (make it scollable if overflow) and after this option list I wanna have volumn price and interval at the left and two icon at right(chart icon and save icon). Just like polymarket. Example A title can be( Nobel Peace Prize 2025 card icon Nobel Peace Prize 2025) and the list can be  (Donald Trump 11% Yes No 89% Elon Musk 2% Yes No). If there is not option list display 2 button Buy Yes (at left) and Buy No (at right).  If any of the button is clicked instead of displaying the 2 button display an input box where they input how much they wanna pay and the button to confirm payment(same as eaither sell or buy button) 


B. Middle East: The culture component should be like the politics component (in A) but the sub-categories should be like this ((All Israel Gaza India-Pakistan Iran Military Actions Khamenei Syria Yemen Lebanon Turkey, etc)

C. Crypto: The cypto component should be like the politics component (in A) but 3 card in a role. I wanna have a side navigation at the left displaying the list of cypro image ans name

D. Tech:  The tech component should be like the politics component (in A) but the sub-categories should be like this (All AI GPT-5 Elon Musk Grok Science SpaceX OpenAI MicroStrategy Big Tech TikTok Meta, etc.. add more)

E. Culture: The culture component should be like the politics component (in A) but the sub-categories should be like this (All Tweet Markets Astronomer Movies Courts Weather GTA VI Kanye Global Temp Mentions Celebrities New Pope Elon Musk Music Pandemics Awards)

F.  World: The world component should be like the politics component (in A) but the sub-categories should be like this (All Bolivia Ukraine Iran Middle East Global Elections India-Pakistan Gaza Israel China Geopolitic, etc)


 G.  Economy: The economy component should be like the politics component (in A) but the sub-categories should be like this Trade War Fed Rates Inflation Taxes Macro Indicators Treasuries.)

H. Sports: For sport component I wanna have the the list of ongoing sport filters first horizontally like a sqaure boxes joined each at the right progressively. Also this filter should be scrollable and lets have pagnation for left and right make this look professional. Inside each box I wanna have (time at top right, volumn price at top left, first club logo and name left and the price at right under the first club  second club logo and name left and the price at right. Under this filter I wanna have the screen divided into 3 column. First column should be side navigation where I wanna have the list of clubs (logo and text at the right of the logo), Second column which is the main column have the categories of sport: Live, starting soon as heading and under each I wanna have cards one card per row, inside the card I wanna have time and volumn at top left and under I wanna have the 2 clubs competing and the right side I wanna have 2 buttons buy or sell, and at the third column it should be like an aside space  where I have the logo, name, the 2 competing teams, under this a nav toggle buy and sell inside each toggle display 2 buttons each displaying the name of the team, under this the amount  and under this a trade button.

I. Elections: For election component I wanna have 3 card in a  row inside the card I wanna have data, county name at the left and their flag at the right. Under this I wanna have the list of contestant percentage, image and name inside a pogress bar also displaying the progress.

J. Note for Trending: Display the cards across from each category  with most and much buy and sell counts (use this order) the component should be like the politics component (in A)

2.When signup or login is clicked a modal should pop up at the center (having 2 input fields of email and walletaddress and a button) same as login. Note that users can use the application by Imputing their Email or Walletaddress. They can use the application with just email and they can use the application with just walletaddress. (Sign up and login modal are same) The modal should be professional looking. (use jwt auth at backend)

3.Details page: The details page should have 2 columns the polls Details in first column and an aside as second column. The polls should have Details, market chart, option list (if available) order book, rules, comment, top holders. For the details I wanna have the logo, title, date, save icon, copy link icon. For the chart please professionaly display the chart, for the order book, please display as people are buying and selling. Based on the input they inout which is sent to database., the rules should be a paragraph and comment. Please program a great comment section with pofessional UI and functioning. At the second column where they buy or sell I wanna have The image and title here also then a toggle between Buy and Sell under each toggle I wanna have 2 button Yes and NO and under this an input box to input the amount they wanna pay and a button trade. Only logged in users should be allowed to send input.

4.For the footer I just wanna have a simple small space like polymarket. Where I have this nav list horizontally align (Bitcoinworld Inc. © 2025 • Privacy • Terms of Use • Learn • Careers • Press) at left and at the right I wanna have social media icons

5.Help me build a professional admin UI where polls are posted and managed. integrate the backend admin api to this and ensure the backend is well built.

Note that anyone can come in the application to view the data. But to post polls they need to login. And everythings in the UI should be functional

For the backend: please help me with a script to populate data on the platform after building the backend. Let the dummy data be much for each filter.

Help me with a doc along that list all the APIs and their functions and sample data. Please a perfect amazing prediction market based on what I’m tying to describe in my description. And let the UI looks so cool.



