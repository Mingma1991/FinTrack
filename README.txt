FinTrack PWA package
====================

यो ZIP मा index.html, manifest.webmanifest, sw.js र icon.svg छन्।

चलाउने:
1. ZIP extract गर्नुहोस्।
2. सबै फाइलहरू GitHub repository को root मा upload/replace गर्नुहोस्।
3. GitHub Pages पहिले नै enable छ भने केही बेरपछि वेबसाइट refresh गर्नुहोस्।
4. iPhone मा Safari बाट live website खोल्नुहोस् > Share > Add to Home Screen।

फिचर:
- Dashboard: income, expense, loan, savings र balance
- कारोबार थप्ने, खोज्ने र हटाउने
- मासिक/वार्षिक रिपोर्ट
- बचत लक्ष्य र सरल चार्ट
- बिलको फोटोबाट OCR (English/Korean text); सम्भावित transaction type सुझाव
- CSV, Excel र JSON backup/restore
- नेपाली आवाजबाट विवरण भर्ने सुविधा (ब्राउजरले समर्थन गरेमा)

महत्त्वपूर्ण:
- OCR ले बिलको रकम वा प्रकार गलत पढ्न सक्छ। Save गर्नु अघि जाँच्नुहोस्।
- फोटो OCR पहिलो पटक चलाउँदा इन्टरनेट चाहिन्छ।
- यो संस्करणमा OCR स्थानीय browser बाट हुन्छ; कुनै बाह्य AI ले खाताको प्रकार निश्चित गर्दैन।
- कारोबार localStorage मा यही browser/device मा रहन्छ। अर्को फोन वा browser मा आफैं sync हुँदैन।
- अपडेट अघि पुरानो कारोबारको JSON backup डाउनलोड गर्नुहोस्।
- यस ZIP मा backend login/cloud sync छैन।
