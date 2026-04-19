# Ways2Well Recipes

A curated collection of **14 grain-free, high-protein lunch recipes** organized into a 4-week rotation. Each recipe is formatted with [schema.org Recipe microdata](https://schema.org/Recipe) for one-click import into recipe management apps like **AnyList**, **Paprika**, and others that support the standard.

## Live Site

Browse the recipes at: **https://jamespederson1.github.io/ways2well-recipes/**

## Recipes

**Week 1**
- Mediterranean Chicken & Cauliflower Rice Bowl
- Thai Coconut Curry Beef with Vegetables
- Lemon Herb Salmon with Roasted Vegetables
- Italian Sausage & Pepper Skillet

**Week 2**
- Korean-Style Beef Lettuce Cups (Bulgogi)
- Tuscan Chicken with Spinach & Sun-Dried Tomatoes
- Moroccan Lamb & Eggplant Tagine
- Buffalo Chicken Cauliflower Casserole

**Week 3**
- Greek Lemon Chicken with Cucumber Salad
- Cajun Shrimp & Andouille Skillet
- Carnitas Bowls with Avocado & Slaw
- Ginger Chicken Meatballs with Bok Choy

**Week 4**
- Beef & Broccoli with Cauliflower Rice
- Pesto Salmon with Roasted Vegetable Medley

## Recipe Characteristics

- **Grain-free** — no wheat, rice, corn, or oats
- **High protein** — 44–54g protein per serving
- **Moderate-fat, low-carb** — each meal targets ~500–540 kcal
- **5 servings per recipe** — sized for a weekly Sunday batch-prep
- **Freezer-friendly** — freezer notes included where perishables (feta, cucumber, fresh herbs) need to stay separate

## How to Import into AnyList

1. Install the [AnyList Recipe Import extension](https://www.anylist.com/recipes/browser-extensions) for your browser
2. Visit each recipe page on the [live site](https://jamespederson1.github.io/ways2well-recipes/)
3. Click the AnyList extension icon in your browser toolbar
4. The recipe imports directly into your AnyList account with ingredients, directions, servings, and timing

## Format

Each HTML page includes:
- `application/ld+json` script block with schema.org Recipe structured data
- Microdata attributes on the rendered HTML (`itemprop="name"`, `itemprop="recipeIngredient"`, etc.)
- ISO 8601 duration metadata (e.g., `PT25M` for 25 minutes)

Both formats are standard and recognized by major recipe import tools.

## License

Recipes are free to use, adapt, and share. Attribution appreciated but not required.
