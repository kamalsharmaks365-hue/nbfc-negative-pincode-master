# NBFC Negative Pincode Master

## Overview
यह एक comprehensive database है जिसमें भारत के सभी states, districts, cities और areas की जानकारी है। हर area के लिए pincode और negative flag दिया हुआ है।

## Columns Description

| Column | Description |
|--------|-------------|
| **State** | भारत के states |
| **District** | हर state का district |
| **City** | District का city/town |
| **Area/Locality** | City के अंदर specific area/locality |
| **Pincode** | 6-digit postal code |
| **Negative Flag** | Yes = NBFC के लिए unserviceable, No = serviceable |
| **Reason** | अगर negative है तो क्यों (Optional) |

## Negative Flag Reasons

- **Remote Rural Area** - दूर का गाँव, कम आबादी
- **Low Banking Penetration** - बहुत कम लोगों के पास बैंक खाता
- **Hilly Terrain** - पहाड़ी इलाका
- **Tribal Area** - आदिवासी इलाका
- **Border Area** - सीमावर्ती क्षेत्र
- **Industrial Area** - सिर्फ industrial use
- **High Default Rate** - ज्यादा loan default होते हैं
- **Low Economic Development** - गरीब इलाका
- **Unauthorized Area** - अनियमित कॉलोनी

## File Format
- **CSV Format** - Excel में easily open हो सकता है
- **Download**: `nbfc_negative_pincode_master.csv`

## How to Use

1. **GitHub से download करो**: nbfc_negative_pincode_master.csv
2. **Excel में खोलो** (Excel automatically separate करेगा)
3. **Filter करो** negative flag के अनुसार
4. **अपनी जरूरत के अनुसार data use करो**

## Data Contribution
अगर और data add करना है या corrections करने हैं, तो:
- Issues create करो
- Pull Request भेजो
- या सीधे contact करो

---

**Last Updated**: August 2026
**Format**: CSV (Excel Compatible)
**Coverage**: Pan-India (All States)