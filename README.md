### Project title
#### Shark Tank India season-1 data analysis using python
### Project Description
#### Shark Tank India is an Indian Hindi-language business reality television series that airs on Sony Entertainment Television. The show is the Indian franchise of the American show Shark Tank. It shows entrepreneurs making business presentations to a panel of investors or sharks, who decide whether to invest in their company. The first season of Shark Tank India premiered on 20 December 2021, and concluded on 4 February 2022.
### DataSet Description
#### 1.Episode_number - Number of the episode
#### 2.Pitch_number - Number of the Pitch
#### 3.Brand_name - Name of the brand Idea
#### 4.Idea - behind the brand building Deal
#### 5.Deal - done or not ; 1 - YES, 0 - NO
#### 6.Pitcher_ask_amount - Amount asked by the pitchers
#### 7.Ask_equity - Equity offered by the pitchers
#### 8.Ask_valuation - Valuation asked by pitchers
#### 9.Deal_amount - Final Deal Amount
#### 10.Deal_equity - Final Deal equity percentage
#### 11.Deal_valuation - Final Valuation of Company after Deal
#### 12.Ashneer_present - Ashneer was present during the pitching ; 1 - YES, 0 - NO
#### 13.Anupam_present - Anupam was present during the pitching ; 1 - YES, 0 - NO
#### 14.Aman_present - Aman was present during the pitching ; 1 - YES, 0 - NO
#### 15.Namita_present - Namita was present during the pitching ; 1 - YES, 0 - NO
#### 16.Vineeta_present - Vineeta was present during the pitching ; 1 - YES, 0 - NO
#### 17.Peyush_present - Peyush was present during the pitching ; 1 - YES, 0 - NO
#### 18.Ghazal_present - Ghazal was present during the pitching ; 1 - YES, 0 - NO
#### 19.Ashneer_deal - Ashneer is a part of Final Deal ; 1 - YES, 0 - NO
#### 20.Anupam_deal - Anupam is a part of Final Deal ; 1 - YES, 0 - NO
#### 21.Aman_deal - Aman is a part of Final Deal ; 1 - YES, 0 - NO
#### 22.Namita_deal - Namita is a part of Final Deal ; 1 - YES, 0 - NO
#### 23.Vineeta_deal - Vineeta is a part of Final Deal ; 1 - YES, 0 - NO
#### 24.Peyush_deal - Peyush is a part of Final Deal ; 1 - YES, 0 - NO
#### 25.Ghazal_deal - Ghazal is a part of Final Deal ; 1 - YES, 0 - NO
#### 26.Total_sharks_invested - Number of total sharks invested in the Company
#### 27.Amount_per_shark - Amount per shark invested
#### 28.Equity_per_shark - Final Equity gained per Shark
### Analysis Metrics
#### 1.Pitch Success
#### 2.Shark Behavior
#### 3.Industry Trends
#### 4.Valuation Analysis


### Analysis and Visualization
#### ![Screenshot 2024-09-26 201936](https://github.com/user-attachments/assets/43418363-4cc4-42d8-8255-30f36b7b2dfc)
#### The bar plot represents the Deal success rate.
#### The number of deals made (about 65) is slightly higher than deals not made (about 52).
#### The success rate appears to be around 55-60%
#### There's a relatively balanced distribution between successful and unsuccessful pitches.This indicates that while more pitches result in deals than not, there's still a significant chance of not securing an investment, reflecting the competitive and selective nature of the show.

#### ![Screenshot 2024-09-26 202001](https://github.com/user-attachments/assets/0b5562d8-6a85-49d0-b128-19792486c82f)
#### The above scatter plot represents the relation between Ask Valuation vs Ask Equity.
#### Most deals cluster in the lower left corner, indicating lower valuations and equity asks.There's a mix of successful (blue) and unsuccessful (red) deals across the range.Successful deals tend to have lower ask valuations and moderate equity asks.There's no clear cutoff between successful and unsuccessful deals based solely on these factors.

#### ![Screenshot 2024-09-26 202046](https://github.com/user-attachments/assets/2c1d0494-d312-49fb-ba3a-072d9864feb9)
#### The above plot represents Top 10 Equity Deals in Shark Tank India Season 1.Sid07 Designs received the highest equity deal at around 70%.Booz scooters and Isak Fragrances both got deals for about 50% equity.Most top deals fall in the 30-50% equity range.The lowest equity deal in the top 10 is still relatively high at about 30%.These high equity percentages suggest that for these top deals, sharks took significant ownership stakes in exchange for their investment and expertise.

#### ![Screenshot 2024-09-26 202110](https://github.com/user-attachments/assets/c0d7fb77-069f-4070-be93-496abffa8c68)
#### This bar chart displays the frequency of different shark combinations making investments.Solo investments (represented by the tallest bar) were by far the most common, occurring over 50 times.The second most frequent combination involves 2-3 sharks investing together, but occurs much less often than solo deals.There's a long tail of various shark combinations, each occurring only a few times.Full panel investments (all sharks together) appear to be rare.This indicates that sharks often preferred to invest alone, but occasionally teamed up for certain deals.

#### ![Screenshot 2024-09-26 202127](https://github.com/user-attachments/assets/6e94cec1-f3fe-468d-ad22-ff71eb960307)
#### This bar chart shows the number of deals made by each shark on the show.Peyush made the most deals with around 28 investments.Aman comes in second with approximately 29 deals.Anupam and Namita have similar deal numbers, around 24 and 22 respectively.Ashneer made about 21 deals.Vineeta invested in roughly 15 companies.Ghazal made the fewest deals, with only about 7 investments.This suggests that Peyush and Aman were the most active investors on the show, while Ghazal was the most selective or had fewer opportunities to invest.

#### ![Screenshot 2024-09-26 202143](https://github.com/user-attachments/assets/8a23af76-7718-4ee3-add1-5c767ce9e34e)
#### This bar chart compares investment amounts for deals involving all five sharks.Four deals are shown where all five sharks invested together.Investment amounts vary significantly among these deals, ranging from about 50 to 100 lakhs.Skippi Pops, IN A CAN, and Sunfox Technologies received similar high investments around 100 lakhs.These all-shark deals represent significant investments, likely in highly promising companies.This chart highlights that when all sharks agree to invest together, it usually results in substantial funding, though the exact amount can still vary based on the specific business.

#### ![Screenshot 2024-09-26 202200](https://github.com/user-attachments/assets/acb704ed-f587-4342-a297-1990b31c4925)
#### This bar chart displays average investment amounts across various industries.There's significant variation in investment amounts across industries.Some industries, like FMCG and food-related businesses, tend to receive higher average investments.Tech-related industries show mixed results, with some receiving high investments and others lower.Traditional industries like textiles or handicrafts generally receive lower average investments.Niche or specialized industries often see higher investment amounts, possibly due to their unique market positions.This suggests that industry type plays a crucial role in determining investment amounts, with sharks favoring certain sectors over others.

#### ![Screenshot 2024-09-26 202224](https://github.com/user-attachments/assets/de59f351-f324-46f2-a8e0-c421bb1c697a)
#### This histogram shows the frequency distribution of valuation gaps.The distribution is heavily right-skewed with a peak near zero.Most valuation gaps fall within a small positive range, suggesting sharks often offer slightly higher valuations than asked.There's a long tail extending to the right, indicating some cases of very large positive valuation gaps.Few negative valuation gaps are observed, implying sharks rarely undervalue companies significantly.The distribution suggests that moderate overvaluations are more common than undervaluations.

#### ![Screenshot 2024-09-26 202249](https://github.com/user-attachments/assets/5cc8d978-9ac6-43ed-85ed-fc29ec676aa6)
#### This scatter plot compares deal amounts to valuation gap percentages.Most deals cluster in the 0-100 lakhs range with valuation gaps between 0% and 100%.There's a wide spread of valuation gaps for similar deal amounts, indicating factors beyond deal size affect valuations.A few outliers show very large negative valuation gaps, suggesting occasional significant undervaluations.No clear linear relationship between deal amount and valuation gap is visible.Larger deals (>100 lakhs) seem to have smaller valuation gaps, clustering closer to 0%.This implies that while deal size may influence valuation gaps, other factors like industry, growth potential, or individual shark preferences also play significant roles.

#### ![Screenshot 2024-09-26 202305](https://github.com/user-attachments/assets/781332e5-75c9-41e4-9581-0cd4d363c264)
#### This bar chart shows the average valuation gap for different shark combinations.Most combinations have positive valuation gaps, indicating sharks often value companies higher than asked.There's significant variation in valuation gaps across different shark combinations.Two combinations (around 15-16 on the x-axis) show large negative gaps, suggesting these sharks tend to value companies much lower than asked.Solo investments (0 on x-axis) generally have positive valuation gaps.Some combinations consistently offer higher valuations than others.







