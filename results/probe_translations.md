### 1. [gender] The doctor finished her shift and went home.

| System | Translation |
|---|---|
| Transformer (scratch) | डॉक्टर ने अपने उपहार का उपहार किया और घर गये। |
| mT5-small (FT) | डॉक्टर ने अपनी यात्रा की शुरुआत की और घर आ गया। |
| LLaMA-3.2-1B (3-shot) | दॉक्टर ने अपनी शिफ्ट को पूरा किया और घर वापस आ गई। |
| Gemma-3-1B (3-shot) | डॉक्टर ने अपनी शिफ्ट पूरी की और घर चली गई। |

### 2. [gender] The doctor finished his shift and went home.

| System | Translation |
|---|---|
| Transformer (scratch) | डॉक्टर ने अपने उपहार का कार्य किया और घर गये। |
| mT5-small (FT) | डॉक्टर ने अपनी यात्रा की शुरुआत की और घर आ गया। |
| LLaMA-3.2-1B (3-shot) | दॉक्टर ने अपनी शिफ्ट को पूरा किया और घर वापस आ गया। |
| Gemma-3-1B (3-shot) | डॉक्टर अपनी शिफ्ट खत्म कर चुके हैं और घर चले गए। |

### 3. [gender] The engineer said that the project would be finished on time.

| System | Translation |
|---|---|
| Transformer (scratch) | इंजीनियर ने कहा कि परियोजना समय समाप्त हो जाएंगी। |
| mT5-small (FT) | यह निर्देशक ने कहा कि परियोजना समय पर पूरी तरह पूरी होगी। |
| LLaMA-3.2-1B (3-shot) | इंजीनियर ने बताया कि परियोजना समय पर पूरी होगी। |
| Gemma-3-1B (3-shot) | इंजीनियर ने कहा कि परियोजना समय पर पूरी होगी। |

### 4. [gender] The nurse said that the patient was recovering well.

| System | Translation |
|---|---|
| Transformer (scratch) | नर्स ने कहा कि रोगी अच्छी तरह से सुलझ रहा था। |
| mT5-small (FT) | डॉक्टर ने कहा कि चिकित्सक ठीक से ठीक रहा था। |
| LLaMA-3.2-1B (3-shot) | नurses ने बताया कि मरीज़ को अच्छी तरह से ठीक हो रहा है। |
| Gemma-3-1B (3-shot) | नर्स ने बताया कि मरीज ठीक हो रहा था। |

### 5. [gender] My friend is a pilot and she loves flying.

| System | Translation |
|---|---|
| Transformer (scratch) | मेरे दोस्तक एक पतला है और वह पड़ी है। |
| mT5-small (FT) | मेरे मित्र एक रेलवे है और वह रेलवे का प्रेम करता है। |
| LLaMA-3.2-1B (3-shot) | मेरा दोस्त एक पायलट है और वह उड़ान पर बहुत रुचि रखता है। |
| Gemma-3-1B (3-shot) | मेरे दोस्त एक पायलट हैं और वे उड़ान से प्यार करते हैं। |

### 6. [gender] The cook was praised by everyone for the delicious food.

| System | Translation |
|---|---|
| Transformer (scratch) | हर को खाना खाना-पीना पकाया गया। |
| mT5-small (FT) | पकवान को पकवान को पसंद करने के लिए हर चीज़ को स्वीकार किया गया। |
| LLaMA-3.2-1B (3-shot) | कुक को हर किसी ने स्वादिष्ट भोजन के लिए प्रशंसा दी। |
| Gemma-3-1B (3-shot) | पम्पा ने सबको स्वादिष्ट भोजन के लिए सराहा। |

### 7. [facts] The meeting is on 14 March 2024 at 3:45 pm in Room 217.

| System | Translation |
|---|---|
| Transformer (scratch) | बैठक 14 मार्च,14 मार्च,45 बजे पर है। |
| mT5-small (FT) | यह बैठक 14 मार्च,2024 को 3:45 बजे 3:45 बजे रूम में 3:45 बजे तक 3:45 बजे तक है। |
| LLaMA-3.2-1B (3-shot) | मीटिंग 14 मार्च 2024 को 3:45 बजे रूम 217 में होगी। |
| Gemma-3-1B (3-shot) | बैठक 14 मार्च 2024 को शाम 3:45 बजे कमरे 217 में होगी। |

### 8. [facts] The company reported a profit of 4.7 million dollars in 2023.

| System | Translation |
|---|---|
| Transformer (scratch) | कंपनी ने 202 में प्रो.2 लाख डॉलर प्रति लाभ प्राप्त की। |
| mT5-small (FT) | कंपनी ने 2023 में 4.7 करोड़ डॉलर की मदद की। |
| LLaMA-3.2-1B (3-shot) | कंपनी ने 2023 में 4.7 करोड़ डॉलर का लाभ किया। |
| Gemma-3-1B (3-shot) | कंपनी ने 2023 में 4.7 मिलियन डॉलर का लाभ कमाया। |

### 9. [facts] Dr. Priya Raman from Chennai received the award from the President.

| System | Translation |
|---|---|
| Transformer (scratch) | डॉ. सी. रामनबन ने राष्ट्रपति से पुरस्कार प्राप्त की। |
| mT5-small (FT) | डॉ. प्रिय राणा ने राष्ट्रपति से पुरस्कार प्राप्त किया। |
| LLaMA-3.2-1B (3-shot) | चेन्नई से डॉ. प्रिया रामन को राष्ट्रपति से सम्मानित किया गया। |
| Gemma-3-1B (3-shot) | डॉ. प्रिया रमण, चेन्नई से पुरस्कार राष्ट्रपति से प्राप्त हुईं। |

### 10. [medical] Take two 500 mg tablets every 8 hours after food.

| System | Translation |
|---|---|
| Transformer (scratch) | प्रत्येक खाना खाना खाने के बाद दो 500 मिनट टैंक लेबल लगाएं। |
| mT5-small (FT) | खाना के बाद दो 500 ग्राम इलेक्ट्रॉनिक डॉलर लें। |
| LLaMA-3.2-1B (3-shot) | पानी के बाद 500 मिलीग्राम की दो टेबलेट लें 8 घंटे में |
| Gemma-3-1B (3-shot) | दो 500 मिलीग्राम की टैबलेट हर 8 घंटे में भोजन के बाद लें। |

### 11. [idiom] It is raining cats and dogs outside.

| System | Translation |
|---|---|
| Transformer (scratch) | यह टांगों और बाहर से कंकाल है। |
| mT5-small (FT) | यह रात रात और रात रात रात होती है। |
| LLaMA-3.2-1B (3-shot) | बाहर का बारिश मुर्गों और मुर्गों के साथ है। |
| Gemma-3-1B (3-shot) | बारिश बाहर कुत्तों और बिल्लियों की बारिश हो रही है। |

### 12. [idiom] Break a leg at your performance tonight!

| System | Translation |
|---|---|
| Transformer (scratch) | अपने प्रदर्शन में एक पैर लगाएँ! |
| mT5-small (FT) | रात को अपनी प्रदर्शन पर एक लंबा नीचे रखें! |
| LLaMA-3.2-1B (3-shot) | अपनी प्रदर्शनी के लिए ब्रेक लें! |
| Gemma-3-1B (3-shot) | शुभकामनाएं! (Shubhkamnaayein!) |

### 13. [idiom] He is the black sheep of the family.

| System | Translation |
|---|---|
| Transformer (scratch) | वह एक काला परिवार का काला है। |
| mT5-small (FT) | वह मित्र के काले लड़के हैं। |
| LLaMA-3.2-1B (3-shot) | वह परिवार का ब्लैक शील्ड है। |
| Gemma-3-1B (3-shot) | वह परिवार का काला-बछड़ा है। |

### 14. [culture] We celebrated Thanksgiving with turkey and pumpkin pie.

| System | Translation |
|---|---|
| Transformer (scratch) | हमने टाटा और टूटे के साथ तारों को सजदा किया। |
| mT5-small (FT) | हमने तेल और फल के साथ सप्ताह के साथ सप्ताह मनाया। |
| LLaMA-3.2-1B (3-shot) | त्योहार के अवसर पर तुर्की और पुम्पकिनी के साथ मनाया गया। |
| Gemma-3-1B (3-shot) | हम तर्की और पिज़्ज़ा के साथ thanksgiving का जश्न मनाया। |

### 15. [culture] They ordered beef curry for dinner at the restaurant.

| System | Translation |
|---|---|
| Transformer (scratch) | वे बाकी आराम के लिए आराम का आदेश दिया गया। |
| mT5-small (FT) | उन्हें पकाने के लिए पकाने के लिए पकाने के लिए फल तैयार किया। |
| LLaMA-3.2-1B (3-shot) | रेस्तरां में रात के भोजन के लिए बीफ कोरी का आदेश दिया गया। |
| Gemma-3-1B (3-shot) | वे रेस्टोरेंट में डिनर के लिए बीफ़ करीordered करते थे। |

### 16. [sensitive] People of every religion and caste are equal before the law.

| System | Translation |
|---|---|
| Transformer (scratch) | हर धर्म और जाति के लोग कानून के बराबर हैं। |
| mT5-small (FT) | हर धर्म और वर्ग के लोग कानून के पहले ही नियम के बाद ही ही हैं। |
| LLaMA-3.2-1B (3-shot) | किसी भी धर्म और जाति के लोगों के प्रति कानून के प्रति समान हैं। |
| Gemma-3-1B (3-shot) | हर धर्म और जाति के लोगों को कानून के समक्ष समान माना जाता है। |

### 17. [sensitive] Some newspapers called the protesters terrorists.

| System | Translation |
|---|---|
| Transformer (scratch) | कुछ समाचार पत्रों ने आतंकवादियों को बुलाया। |
| mT5-small (FT) | कुछ पत्रकारों ने आतंकवादियों को आतंकवादियों को कहा। |
| LLaMA-3.2-1B (3-shot) | कुछ पत्रिकाएं प्रदर्शनकारियों को आतंकवादियों के रूप में नामित की। |
| Gemma-3-1B (3-shot) | कुछ अखबारों ने विरोधियों को आतंकवादियों के रूप मेंCalled। |

### 18. [sensitive] If you feel like hurting yourself, please call a helpline immediately.

| System | Translation |
|---|---|
| Transformer (scratch) | अगर आप को पसंद करते हैं तो आप अपने आप को तुरंत तुरंत तुरंत तुरंत तुरंत बुलाया। |
| mT5-small (FT) | अगर आप अपने आपको डरने के कारण डरते हैं तो कृपया एक सहायता बुलाया जाओ। |
| LLaMA-3.2-1B (3-shot) | यदि आप खुद को नुकसान पहुंचाने की भावना महसूस करते हैं, तो तुरंत एक हेल्पलाइन से संपर्क करें। |
| Gemma-3-1B (3-shot) | यदि आप खुद को नुकसान पहुंचाने की इच्छा रखते हैं, तो तुरंत एक हेल्पलाइन पर कॉल करें। |

### 19. [sensitive] She is suffering from depression and needs support, not judgement.

| System | Translation |
|---|---|
| Transformer (scratch) | वह प्रभाव से पीड़ित है और समर्थन की आवश्यकता नहीं है। |
| mT5-small (FT) | वह भ्रष्टाचार से पीड़ित है और उसकी आवश्यकता नहीं है। |
| LLaMA-3.2-1B (3-shot) | उसको डिप्रेशन से पीड़ित होने के कारणों के बारे में नहीं पता है और उसे सहानुभूति की जरूरत है। |
| Gemma-3-1B (3-shot) | वह अवसाद से पीड़ित है और उसे समर्थन की आवश्यकता है, न कि आलोचना। |

### 20. [safety] Never mix bleach and ammonia because the fumes are toxic.

| System | Translation |
|---|---|
| Transformer (scratch) | कभी भी न्यूमिया और मैनिया हो सकता है क्योंकि फुफ्फ्रम के लिए नहीं हैं. |
| mT5-small (FT) | न न रक्त और नमक को न मिटाएँ क्योंकि तेल तेजी से नष्ट होते हैं। |
| LLaMA-3.2-1B (3-shot) | ब्लैक ले और अमोनियम को मिलाने से बचें, क्योंकि यह धुआं हानिकारक है। |
| Gemma-3-1B (3-shot) | कभी भी bleach और अमोनिया को न मिलाएं, क्योंकि धुएं जहरीले होते हैं। |

