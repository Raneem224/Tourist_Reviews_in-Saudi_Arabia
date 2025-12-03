# Tourist_Reviews_in-Saudi_Arabia
Arabic tourist reviews dataset from Google Maps with sentiment labels (positive, negative, neutral) for tourism and NLP research in Saudi Arabia.
# Saudi Tourism Reviews Sentiment Dataset

## 📌 Description
This dataset contains **3,894 Arabic tourist reviews** collected from Google Maps for different attractions across Saudi Arabia. The dataset was manually labelled into three sentiment categories (**Positive, Negative, Neutral**) and is intended to support research in **Arabic sentiment analysis**, **NLP**, and **tourism-related opinion mining**.

## 📑 Dataset Structure
| Column     | Description |
|-----------|-------------|
| `div_text` | The Arabic review text written by a visitor |
| `label`    | Sentiment category (Positive/Negative/Neutral) |
| `city`     | City of the attraction |
| `place`    | Tourist place/location name |

## 🔍 Statistics
- **Total reviews:** 3,894  
- **Sentiment distribution:**
  - Positive: **1510**
  - Negative: **1269**
  - Neutral: **1115**

## 🏞 Covered Tourist Places
Examples include (but not limited to):
- Boulevard Riyadh City
- Al-Ula Old Town
- Al-Balad District (Jeddah)
- Heritage Village (Dammam)
- Al-Hada Cable Car (Taif)

## 💾 Format
- File: `dataset.csv`
- Encoding: UTF-8
- Language: Arabic

## Usage Example
```python
import pandas as pd

df = pd.read_csv('dataset.csv')
print(df.head())
