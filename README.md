# IndianFoodDatasetGeneration

When I browsed for a Food Recipes (Especially Indian Food) Dataset, I could not find one (that I could use) online. So, I decided to create one.

The dataset following fields (self-explanatory) - ['RecipeName', 'TranslatedRecipeName', 'Ingredients', 'TranslatedIngredients', 'Prep', 'Cook', 'Total', 'Servings', 'Cuisine', 'Course', 'Diet', 'Instructions', 'TranslatedInstructions']. The datset contains a csv and a xls file. Sometimes, the content in Hindi is not visible in the csv format.

So, a lot of entries in the dataset were in Hindi language. To take care of such entries and translating them to English for consistency, I went ahead and used 'googletrans'. It is a python library that implements Google Translate API underneath. The results of the same are in the columns prefixed with 'Translated'

The dataset has been created using Archana's Kitchen Website (https://www.archanaskitchen.com/). It is a great website and hosts a ton of useful content. You should definitely consider viewing it if you are interested.

The dataset can be used to answer a lot of questions related to Food Recipes. You can see the explore the serving sizes, time required to prepare a dish, most common ingredients, different cuisines, diets, courses and what not. I hope this dataset helps the Analytics community.

