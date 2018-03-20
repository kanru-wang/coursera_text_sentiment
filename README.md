## Machine Learning Assignment: Predicting customer sentiments, given product reviews

Logistic regression with L2 regularisation is implemented to predict customer sentiments (either positive or negative) on products, based on their reviews. The predicted sentiments are then compared with the actual sentiments which customers gave. Machine Learning libraries are not used.

Below is a list of the most negative reviews based on model predictions. The "name" column is product names. The "rating" column shows the actual ratings customers gave. 


|              name             |             review            | rating | ... |
--- | --- | --- | ---
| Stork Craft Heather Dressi... | The construction is simply... |  2.0   | ... |
| The First Years True Choic... | Note: we never installed b... |  1.0   | ... |
| Regalo My Cot Portable Bed... | If I could give this produ... |  1.0   | ... |
| Ingenuity Chair Top High C... | I had never wished Amazon ... |  1.0   | ... |
| Fisher-Price Zen Collectio... | THIS BASSINET IS OVERPRICE... |  2.0   | ... |
| Graco ComfortSport Convert... | This is a dreadful car sea... |  1.0   | ... |
| UPPAbaby G-Series Rain Shield | First off do not buy this ... |  1.0   | ... |
| The First Years American R... | This kit is a complete was... |  1.0   | ... |
| VTech Communications Safe ... | First, the distance on the... |  1.0   | ... |
| Peace of Mind Two 900 Mhz ... | If we only knew when we re... |  1.0   | ... |
| Evenflo Crosstown Soft Por... | I'm sure that this product... |  1.0   | ... |
| Summer Infant Sleek and Se... | The first monitor broke wi... |  1.0   | ... |
| Medela Harmony Manual Brea... | I hate this product becaus... |  1.0   | ... |
| Motorola MBP36 Remote Wire... | Our screen broke after 3 m... |  1.0   | ... |
| Philips AVENT Hard Spout M... | These cups - the entire Av... |  2.0   | ... |
| Playtex Diaper Genie Twist... | I wish I had done my resea... |  1.0   | ... |
| Philips AVENT Isis iQ Duo ... | My wife has been sucessful... |  2.0   | ... |
| Cosco Flat-Fold High Chair... | MISSING PIECES!  This item... |  1.0   | ... |
| Belkin WeMo Wi-Fi Baby Mon... | I read so many reviews say... |  2.0   | ... |
| Fisher-Price Rainforest De... | I bought this item for my ... |  1.0   | ... |


In this model, the ten words in reviews that contribute the most to positive sentiments are

[('love', 1.0395285158465861),  
('loves', 1.03126534689187),  
('easy', 0.96736183663147013),  
('perfect', 0.81803783754282045),  
('great', 0.78993514722140434),  
('happy', 0.5452454450870925),  
('best', 0.52323599624032524),  
('little', 0.51691739249147073),  
('fits', 0.47720459131995552),  
('well', 0.44670047396569251)]


The ten words in reviews that contribute the most to negative sentiments are

[('disappointed', -0.93451841994063234),  
 ('money', -0.75381829398395594),  
 ('return', -0.72580656668643029),  
 ('waste', -0.60462025188532653),  
 ('returned', -0.55986984915880289),  
 ('broke', -0.54286058349649569),  
 ('work', -0.51731191046855274),  
 ('thought', -0.4681998280798263),  
 ('idea', -0.45487921362069389),  
 ('cheap', -0.44900997257036723)]
