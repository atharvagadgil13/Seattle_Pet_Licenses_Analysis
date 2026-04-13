"# Seattle_Pet_Licenses_Analysis" 
# Seattle Pet Licenses Analysis

A Tableau-based exploratory data analysis of pet licensing records in the City of Seattle, using the official [Seattle Open Data](https://data.seattle.gov/) dataset (as of September 16, 2025).

## Dataset

The dataset contains **42,659 pet license records** with fields including animal name, species, primary/secondary breed, license issue date, license number, and ZIP code.

**Source:** `Seattle_Pet_Licenses_20250916.csv`

---

## Visualizations

### 1. Species Counts — Text Table
A simple text table showing the count of licensed pets by species. Dogs lead overwhelmingly with 28,791 licenses.

![Species Counts](Screenshot%202025-10-02%20191650.png)

---

### 2. Species Counts — Pie Chart
A pie chart breaking down the species distribution: Dogs (28,791), Cats (13,841), Goats (24), and Pig (3).

![Species Pie Chart](Screenshot%202025-10-02%20191750.png)

---

### 3. Species Counts — Bar Chart
A horizontal bar chart visualizing species counts, filtered to show Dogs. The bar extends to ~28,791.

![Species Bar Chart](Screenshot%202025-10-02%20191836.png)

---

### 4. Species Counts — Tree Map
A treemap visualization showing the relative proportion of each species. Dogs occupy the largest area, followed by Cats.

![Species Tree Map](Screenshot%202025-10-02%20191904.png)

---

### 5. Primary Breed Counts — All Species
A detailed text table listing all 282 unique primary breeds and their counts, sorted in ascending order.

![Primary Breed Counts](Screenshot%202025-10-02%20191929.png)

---

### 6. Primary Breed Counts — Dogs Only
A horizontal bar chart of dog breeds sorted by count. Top breeds:
- Labrador Retriever: 2,742
- Chihuahua, Short Coat: 1,453
- Golden Retriever: 979
- German Shepherd: 872
- Miniature Poodle: 813

![Dog Breeds](Screenshot%202025-10-02%20191952.png)

---

### 7. Primary Breed Counts — Cats Only
A horizontal bar chart of cat breeds sorted by count. Top breeds:
- Domestic Shorthair: 7,694
- Domestic Medium Hair: 1,564
- American Shorthair: 865
- Domestic Longhair: 456
- Siamese: 202

![Cat Breeds](Screenshot%202025-10-02%20192019.png)

---

### 8. Top 15 Pet Names
A bar chart of the 15 most popular pet names across all species. **Luna** takes the top spot, followed by Charlie, Lucy, Daisy, and Bella.

![Top 15 Pet Names](Screenshot%202025-10-02%20192043.png)

---

### 9. Licenses Issued by Week — All Animals
A line chart showing the count of licenses issued per week throughout the year. Licensing activity increases significantly in the second half of the year (weeks 30–50), likely tied to adoption and renewal seasons.

![Licenses by Week](Screenshot%202025-10-02%20192100.png)

---

### 10. Geographic Map — Seattle Pets by ZIP Code
A bubble map of Seattle showing pet license density by ZIP code. Larger bubbles indicate more licenses. North Seattle neighborhoods (98103, 98115, 98117) have the highest concentrations, with over 2,000 licenses each.

![Map](Screenshot%202025-10-02%20192133.png)

---

### 11. Final Dashboard
A combined dashboard featuring the tree map, weekly trend line, geographic map, and breed count tables for a comprehensive overview.

![Final Dashboard](Screenshot%202025-10-02%20192201.png)

---

## Key Insights

- **Dogs account for ~67%** of all licensed pets in Seattle, cats for ~32%, with goats and pigs making up a tiny fraction.
- **Labrador Retriever** is the most popular dog breed by a wide margin; **Domestic Shorthair** dominates cat breeds.
- **Luna** is Seattle's favorite pet name, popular across both dogs and cats.
- Licensing activity **peaks in fall** (weeks 35–50), suggesting seasonal patterns in pet adoption or license renewals.
- **North Seattle** ZIP codes have the highest pet license density, particularly 98103, 98115, and 98117.

## Tools Used

- **Tableau Desktop** — Data visualization and dashboard creation
- **Seattle Open Data Portal** — Data source

## How to Open

1. Install [Tableau Desktop](https://www.tableau.com/products/desktop) or [Tableau Public](https://public.tableau.com/)
2. Open `AtharvaGadgil_Assignment1_DADABI.twb`
3. When prompted, point the data source to `Seattle_Pet_Licenses_20250916.csv`

## Author

**Atharva Gadgil**  
Master's student in Information Systems @ Northeastern University  
[GitHub](https://github.com/atharvagadgil13)
