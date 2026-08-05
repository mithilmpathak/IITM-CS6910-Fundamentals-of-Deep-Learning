# CS6910 Assignment 3 - Task 5 Report Outputs

## Model Convergence (10 Epochs Training Log)
| Epoch | Train Loss | Validation Loss | Status |
|---|---|---|---|
| Epoch 01 | 6.5897 | 5.9628 | Saved Best |
| Epoch 02 | 5.8336 | 5.6041 | Saved Best |
| Epoch 03 | 5.5313 | 5.3882 | Saved Best |
| Epoch 04 | 5.3265 | 5.2455 | Saved Best |
| Epoch 05 | 5.1797 | 5.1478 | Saved Best |
| Epoch 06 | 5.0702 | 5.0784 | Saved Best |
| Epoch 07 | 4.9866 | 5.0244 | Saved Best |
| Epoch 08 | 4.9166 | 4.9796 | Saved Best |
| Epoch 09 | 4.8597 | 4.9438 | Saved Best |
| Epoch 10 | **4.8097** | **4.9164** | **Saved Best** |

---

## Quantitative Results (BLEU Scores on Test Set)
| Metric | Score (%) |
|---|---|
| **BLEU@1** | **14.90** |
| **BLEU@2** | **7.70** |
| **BLEU@3** | **4.28** |
| **BLEU@4** | **2.29** |

---

## 5 Training Sentence Translations

### Example 1
- **Source (English)**: Shops & shopping malls would remain open till 8 pm.
- **Ground Truth (Hindi)**: सभी दुकानों और व्यापारिक प्रतिष्ठानों को दोपहर 2 बजे तक व्यापार करने की अनुमति होगी।
- **Model Output (Hindi)**: सभी शाम को सभी घरों में शाम 8 बजे तक बंद रहेंगे ।

### Example 2
- **Source (English)**: The bench did not accept the plea that the National Human Rights Commission (NHRC), which had earlier issued notice to the state government on the issue, be also made a party in the present proceeding.
- **Ground Truth (Hindi)**: पीयूसीएल ने इस मामले में राष्ट्रीय मानवाधिकार आयोग को भी पक्षकार बनाने का अनुरोध को स्वीकार नहीं किया. मालूम हो कि आयोग ने भी इस मुद्दे पर पहले राज्य सरकार को नोटिस जारी किया था.
- **Model Output (Hindi)**: इस मामले में राज्य सरकार ने इस संबंध में एक बयान जारी किया था , जो राज्य सरकार ने इस मामले में भी इस संबंध में किसी भी फैसले पर सुनवाई की अनुमति नहीं दी थी , जो इस मामले में सरकार को नोटिस जारी किया था ।

### Example 3
- **Source (English)**: Asian Champions Trophy: Indian men's hockey squad announced, Manpreet Singh named captain
- **Ground Truth (Hindi)**: एशियन चैंपियंस ट्रॉफी : भारतीय हॉकी टीम की कप्तानी मनप्रीत सिंह करेंगे
- **Model Output (Hindi)**: भारतीय टीम : भारतीय टीम के कप्तान महेंद्र सिंह धोनी ने भारतीय टीम के कप्तान महेंद्र सिंह धोनी को विश्व कप के लिए टीम के कप्तान महेंद्र सिंह धोनी को बधाई दी है ।

### Example 4
- **Source (English)**: """India should start dialogue with Pakistan so that such incidents do not happen in future."""
- **Ground Truth (Hindi)**: भारत को पाकिस्तान के साथ बातचीत शुरू करनी चाहिए ताकि भविष्य में ऐसी घटनाएं न हों- महबूबा मुफ्ती
- **Model Output (Hindi)**: उन्होंने कहा , ‘‘ भारत में इस मुद्दे पर चर्चा नहीं की जा रही है कि भारत में इस मुद्दे पर चर्चा नहीं की जा रही है कि भारत में इस मुद्दे पर चर्चा नहीं की जा रही है कि भारत में इस तरह की चर्चा की जा सकती है

### Example 5
- **Source (English)**: CSMC today sanctioned 1,69,381 houses for Economically Weaker Sections in 145 cities in 8 states for which a total central assistance of Rs.2,444 cr will be provided.
- **Ground Truth (Hindi)**: सीएसएमसी ने आज 8 राज्‍यों के 145 शहरों में आर्थिक रूप से कमजोर वर्गों के लिए 1,69,381 मकानों की मंजूरी दी।
- **Model Output (Hindi)**: आज , हम आज में 1 , 3 60 शहरों में कुल 3 , 3 50 , 3 50 शहरों में कुल मिलाकर 5 , 3 50 , 3 50 शहरों में सहायता प्रदान की जाएगी ।

---

## 5 Test Sentence Translations

### Example 1
- **Source (English)**: LPF chairman Abdul Halim Abdul Hamid said the board had requested the makers for the alterations in the movie, so that the the viewers continue respecting the law.
- **Ground Truth (Hindi)**: एलपीएफ चेयरमैन अब्दुल हलीम अब्दुल हमीद ने बताया कि फिल्म का अंत बदलने को लेकर निर्माताओं से अनुरोध किया गया था।
- **Model Output (Hindi)**: इस फिल्म के अध्यक्ष मोहम्मद खान ने कहा कि इस फिल्म में इस फिल्म के लिए मुख्य कार्यकारी निदेशक मोहम्मद बिन अब्दुल कलाम के बारे में जानकारी देते हुए कहा कि इस फिल्म में यह स्पष्ट है कि इस फिल्म के लिए यह स्पष्ट है कि इस फिल्म के लिए

### Example 2
- **Source (English)**: During ovulation, the womans immune function is impaired, making the body more susceptible to disease, the study said.
- **Ground Truth (Hindi)**: अध्ययन में कहा गया है कि अंडोत्सर्ग के दौरान महिला की प्रतिरक्षा क्षमता बिगड़ जाती है, जिससे शरीर में बीमारी होने की संभावना अधिक होती है.
- **Model Output (Hindi)**: इस दौरान , एक अध्ययन के दौरान , शरीर के शरीर के अध्ययन के दौरान , शरीर के अध्ययन के दौरान , शरीर के अध्ययन के दौरान , एक अध्ययन के लिए , एक अध्ययन के दौरान , एक अध्ययन के लिए एक अध्ययन के लिए एक अध्ययन के लिए

### Example 3
- **Source (English)**: He's scored 94 goals in total and registered 38 assists.
- **Ground Truth (Hindi)**: उन्होंने 94 कैच लिए और 38 बल्लेबाजों को स्टंप किया।
- **Model Output (Hindi)**: उन्होंने कुल आय में 37 और कुल कुल कुल 36 0 रन की और कुल संख्या बढ़कर 49 0 और 46 0 38 0 और 57 में कुल संख्या बढ़कर 49 और 46 0 से अधिक है ।

### Example 4
- **Source (English)**: One more of the Indian states are going to be connected through rail network.
- **Ground Truth (Hindi)**: भारत का एक राज्य आज एक रेल connectivity से जुड़ रहा है।
- **Model Output (Hindi)**: भारत के एक अन्य राज्यों के माध्यम से एक - एक और एक - एक - एक - एक - एक - एक - एक - एक - एक - एक - एक - एक - एक - एक - एक - एक - एक - एक - एक -

### Example 5
- **Source (English)**: UNESCO is also helping to translate the works of Guru Nanak Dev ji into different languages.
- **Ground Truth (Hindi)**: यूनेस्को द्वारा भी गुरु नानक देव जी की रचनाओं को अलग-अलग भाषाओं में अनुवाद करने में मदद की जा रही है।
- **Model Output (Hindi)**: संयुक्त राष्ट्र के रूप में , श्री राम नाथ मंदिर के विभिन्न भाषाओं में विभिन्न भाषाओं में विभिन्न भाषाओं में शामिल होने के लिए विभिन्न भाषाओं में शामिल हैं ।

