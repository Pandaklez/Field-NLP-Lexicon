# Field-NLP-Lexicon
The project was developed by students of the Master's program in Computational Linguistics 2020-22 Anna Klezovich and Alina Zakharova. 

The tasks of the project included the creation of an RDF database from Andi and Chukchi dictionaries. Links to resources were shared with us by our colleagues from the HSE School of Linguistics. Dictionaries have already been marked up, their structure will be described below. 

Andi dictionary

Format: google spreadsheet. 

Structure: It had columns for “lemma” in Andi, “morphology” column with a list of possible word form endings for this lemma, “pos” with a part of speech tags. “concepticon” column is practically empty, but meant to have a semantic field to which this lemma belongs. “meaning_ru” is the column with a translation(s) to Russian. “ipa” is the column with phonetic representation in IPA (link) of this lemma. Last but not the least, “definition” column presents the dictionary definition of the Andi lemma where basically all previous information is accumulated.

Dictionary volume: 9 378 items.

Source: Comparative Andic dictionary database

Source link: https://github.com/phon-dicts-project/comparative_andic_dictionary_database 

Chukchi dictionary

Format: .txt file
Structure: each dictionary item is called a lexeme. Each lexeme had the following tags: the “lex” tag for a citation form, the "gramm" tag to describe part of speech, the "stem" tag for written representation, e.g. айгоонкэн and the "trans_ru" tag for the translation.

Dictionary volume: 6 278 items.

Source link: https://cloud.mail.ru/public/FpFp/E7FTLRhB2/%D0%9B%D0%B8%D1%82%D0%B5%D1%80%D0%B0%D1%82%D1%83%D1%80%D0%B0/%D0%A1%D0%BB%D0%BE%D0%B2%D0%B0%D1%80%D0%B8/

To create a database of dictionaries were parsed and automatically converted to RDF format. Ontolex markup was applied to the data. 

The dataset we obtained is here: https://drive.google.com/drive/folders/1LnaplC8n5dA4EVtGTN1qf_A66p5ddbx7?usp=sharing

The final product is a database based on marked dictionaries, where one can use SPARQL to find dictionary information on lexical units. In the final product, dictionaries are maximally recognized and all grammatical information is structured within the framework of the ontology. 


Link to the project code: https://github.com/Pandaklez/Field-NLP-Lexicon

Publication link: https://docs.google.com/document/d/1uJWOf6fw32II6Ksc7XeiJv8Z8u2kpOt3T9w3Wix_veI/edit?usp=sharing

Link to the service where the final product is applied: http://87.247.157.119:5000/ 

One can quote us by using these links.HSE CompLing Project 2020-2021.

Here is the link to the final andi RDF and to the dataset we were working with
https://drive.google.com/drive/folders/1LnaplC8n5dA4EVtGTN1qf_A66p5ddbx7?usp=sharing
