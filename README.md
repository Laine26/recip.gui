# code reference: guide by chatgpt open ai
import tkinter as tk

def show_recipe():

    recipe_name = recipe_entry.get()
    recipe_text.delete(1.0, tk.END)
    if recipe_name.lower() == "adobo":
        recipe_text.insert(tk.END, "Recipe for Adobo:\n")
        recipe_text.insert(tk.END, "Ingredients:\n"
                                   "- 2 lbs chicken or pork\n"
                                   "- 1 cup soy sauce\n"
                                   "- 1 cup vinegar\n"
                                   "- 1 head garlic, minced\n"
                                   "- 1 onion, chopped\n"
                                   "- 1 tsp peppercorns\n"
                                   "- 2-3 bay leaves\n"
                                   "- 1 cup water\n"
                                   "- Cooking oil\n"
                                   "- Salt and pepper to taste\n\n")
        recipe_text.insert(tk.END, "Instructions:\n"
                                   "1. In a pot, combine soy sauce, vinegar, garlic, onion, peppercorns, and bay leaves.\n"
                                   "2. Add the chicken or pork and marinate for at least 30 minutes.\n"
                                   "3. Add water and bring to a boil. Reduce heat and simmer until meat is tender.\n"
                                   "4. Heat cooking oil in a separate pan and fry the meat until browned.\n"
                                   "5. Add the meat to the sauce and simmer for another 10-15 minutes.\n"
                                   "6. Season with salt and pepper to taste.\n"
                                   "7. Serve hot with rice.\n\n")
    elif recipe_name.lower() == "sinigang":
        recipe_text.insert(tk.END, "Recipe for Sinigang:\n")
        recipe_text.insert(tk.END, "Ingredients:\n"
                                   "- 1 lb pork ribs or belly\n"
                                   "- 1 pack sinigang mix\n"
                                   "- 1 onion, sliced\n"
                                   "- 2 tomatoes, quartered\n"
                                   "- 1 daikon radish, sliced\n"
                                   "- 1 eggplant, sliced\n"
                                   "- 1 bundle string beans\n"
                                   "- 2-3 green chili peppers\n"
                                   "- Salt to taste\n\n")
        recipe_text.insert(tk.END, "Instructions:\n"
                                   "1. In a pot, boil pork in water until tender.\n"
                                   "2. Add onions and tomatoes, then simmer until vegetables are tender.\n"
                                   "3. Add sinigang mix and stir.\n"
                                   "4. Add daikon radish, eggplant, string beans, and green chili peppers.\n"
                                   "5. Season with salt to taste.\n"
                                   "6. Simmer for a few more minutes.\n"
                                   "7. Serve hot with rice.\n\n")
    elif recipe_name.lower() == "lumpia shanghai":
        recipe_text.insert(tk.END, "Recipe for Lumpia Shanghai:\n")
        recipe_text.insert(tk.END, "Ingredients:\n"
                                   "- 1/2 lb ground pork\n"
                                   "- 1/2 cup shrimp, minced\n"
                                   "- 1 carrot, grated\n"
                                   "- 1/2 cup green onions, chopped\n"
                                   "- 2 cloves garlic, minced\n"
                                   "- 1 egg\n"
                                   "- 1/4 cup soy sauce\n"
                                   "- Lumpia wrappers\n"
                                   "- Cooking oil\n"
                                   "- Salt and pepper to taste\n\n")
        recipe_text.insert(tk.END, "Instructions:\n"
                                   "1. In a bowl, combine ground pork, minced shrimp, grated carrot, chopped green onions, minced garlic, egg, and soy sauce.\n"
                                   "2. Season with salt and pepper to taste.\n"
                                   "3. Place a spoonful of the mixture onto a lumpia wrapper and roll tightly, sealing the edges with water.\n"
                                   "4. Heat cooking oil in a pan and fry lumpia until golden brown and crispy.\n"
                                   "5. Serve hot with sweet chili sauce for dipping.\n\n")
    elif recipe_name.lower() == "chicken tinola":
        recipe_text.insert(tk.END, "Recipe for Chicken Tinola:\n")
        recipe_text.insert(tk.END, "Ingredients:\n"
                                   "- 1 lb chicken, cut into serving pieces\n"
                                   "- 1 knob ginger, sliced\n"
                                   "- 2 cloves garlic, minced\n"
                                   "- 1 onion, sliced\n"
                                   "- 2 cups water\n"
                                   "- 1 cup green papaya, sliced\n"
                                   "- 1 cup spinach\n"
                                   "- Fish sauce to taste\n"
                                   "- Cooking oil\n\n")
        recipe_text.insert(tk.END, "Instructions:\n"
                                   "1. In a pot, sauté ginger, garlic, and onion in cooking oil until fragrant.\n"
                                   "2. Add chicken pieces and cook until slightly brown.\n"
                                   "3. Pour water and bring to a boil. Simmer until chicken is tender.\n"
                                   "4. Add green papaya slices and cook until tender.\n"
                                   "5. Add spinach and cook until wilted.\n"
                                   "6. Season with fish sauce to taste.\n"
                                   "7. Serve hot with rice.\n\n")
    elif recipe_name.lower() == "beef caldereta":
        recipe_text.insert(tk.END, "Recipe for Beef Caldereta:\n")
        recipe_text.insert(tk.END, "Ingredients:\n"
                                   "- 1 lb beef, cubed\n"
                                   "- 3 potatoes, peeled and quartered\n"
                                   "- 2 carrots, sliced\n"
                                   "- 1 bell pepper, sliced\n"
                                   "- 1 onion, chopped\n"
                                   "- 4 cloves garlic, minced\n"
                                   "- 1 can liver spread\n"
                                   "- 1 cup tomato sauce\n"
                                   "- 2 cups beef broth\n"
                                   "- 2 tbsp soy sauce\n"
                                   "- 2 tbsp cooking oil\n"
                                   "- Salt and pepper to taste\n\n")
        recipe_text.insert(tk.END, "Instructions:\n"
                                   "1. In a pan, heat cooking oil and sauté garlic and onion until fragrant.\n"
                                   "2. Add beef cubes and cook until browned.\n"
                                   "3. Pour tomato sauce, beef broth, and soy sauce. Bring to a boil.\n"
                                   "4. Simmer until beef is tender.\n"
                                   "5. Add potatoes and carrots, cook until vegetables are tender.\n"
                                   "6. Stir in liver spread until well combined.\n"
                                   "7. Add bell peppers and season with salt and pepper to taste.\n"
                                   "8. Simmer for a few more minutes.\n"
                                   "9. Serve hot with rice.\n\n")
    else:
        recipe_text.insert(tk.END, f"Recipe for {recipe_name} is not in the list.")

root = tk.Tk()
root.title("Recipe Menu")

recipe_label = tk.Label(root, text="Enter Recipe:", font=("Arial", 14))
recipe_label.grid(row=0, column=0, padx=10, pady=5, sticky="e")
recipe_entry = tk.Entry(root, font=("Arial", 14))
recipe_entry.grid(row=0, column=1, padx=10, pady=5)

show_button = tk.Button(root, text="Show Recipe", command=show_recipe, font=("Arial", 14))
show_button.grid(row=0, column=2, padx=10, pady=5)

recipe_text = tk.Text(root, width=60, height=15, font=("Arial", 12))
recipe_text.grid(row=1, column=0, columnspan=3, padx=10, pady=5)

root.mainloop()
