# Pokemon-Slab-Scanner
A wireless computer vision tool that scans graded Pokémon cards, uses OCR and image processing to identify the card and the grade and fetches current market prices from several APIs. Designed to deliver quick, precise price information and automate card value.

# Overview
The process of detecting graded Pokémon cards and calculating their current market worth is automated by the Pokémon slab scanner. Key slab information, including card name, set, number, grade and certifications ID, is extracted by the system using image processing, OCR and card matching logic. In order to provide precise, current valuations, it then searches many pricing APIs. This project showcases real engineering abilities in full-slack development, OCR, computer vision, and API integration.

# Features
Slab photos are cleaned and ready for OCR using image preprocessing.
Label text (card name, set, grade, cert number) is read by OCR processing.
Card Identification compares data that has been gathered to known Pokémon card entries.
Real time pricing takes market prices from sites like PriceCharting, eBay, and TCGplayer.
Wireless Work allows for embedded or mobile camera scanning
Structured output provides a pricing summary and validated card information.

# Folder Descriptions
src- main engine. OCR, imagine processing, price logic
models- ML/OCR models
Api- pricing APi models
app- user interface
docs- documentation

# Tech stack 
python- core logic, OCR, imagine processing
OpenCV- label text extraction
Fast Api- backend Api
React- mobile/web app
TCGplayer, eBay, priceCharting Apis- pricing data

# How It Works
1. User scans or uploads a slab image
2. image is preprocessed
3. OCR extracts label text
4. card identification logic validates card details
5. pricing APIs are queried
6. Final structured result is returned to the user
