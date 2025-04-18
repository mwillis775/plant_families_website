# Plant Families Website Structure

## Overview
This website will present plant families in phylogenetic order with an intuitive and fun interface. The site will focus on teaching users about plant family characteristics and how to identify them in the field.

## Main Pages

### 1. Home Page
- **Purpose**: Welcome users and provide an overview of the website
- **Key Elements**:
  - Brief introduction to plant phylogeny
  - Visual teaser of the interactive phylogenetic tree
  - Featured plant families (rotating selection)
  - Navigation to main sections
  - Search functionality

### 2. Phylogenetic Tree Explorer
- **Purpose**: Interactive visualization of plant evolutionary relationships
- **Key Elements**:
  - Zoomable, interactive phylogenetic tree
  - Color-coded plant groups (bryophytes, pteridophytes, gymnosperms, angiosperms)
  - Clickable nodes that lead to family information pages
  - Timeline of plant evolution
  - Filtering options (by major group, habitat, etc.)

### 3. Family Information Pages
- **Purpose**: Detailed information about each plant family
- **Key Elements**:
  - Family name and classification information
  - Key characteristics with visual aids
  - Field identification tips
  - Common examples with images
  - Distribution information
  - Ecological importance
  - Related families (phylogenetically close)

### 4. Field Identification Guide
- **Purpose**: Practical guide for identifying plants in the field
- **Key Elements**:
  - Visual keys based on easily observable traits
  - Decision trees for identification
  - Seasonal identification tips
  - Habitat-based guides
  - Printable field sheets

### 5. About Page
- **Purpose**: Information about the website and its purpose
- **Key Elements**:
  - Explanation of phylogenetic classification
  - Information about APG IV system
  - Credits and references
  - Contact information

## Navigation Structure

```
Home
├── Phylogenetic Tree Explorer
│   ├── Overview Tree
│   ├── Non-Flowering Plants
│   │   ├── Bryophytes
│   │   ├── Pteridophytes
│   │   └── Gymnosperms
│   └── Flowering Plants (Angiosperms)
│       ├── Magnoliids
│       ├── Monocots
│       └── Eudicots
├── Plant Families (A-Z)
│   ├── Amaranthaceae
│   ├── Amaryllidaceae
│   ├── Anacardiaceae
│   └── ... (all families)
├── Field Identification
│   ├── By Structure (Leaves, Flowers, Fruits)
│   ├── By Habitat
│   ├── By Season
│   └── Printable Guides
└── About
    ├── Plant Classification
    ├── References
    └── Contact
```

## User Flow

1. User lands on Home page
2. User can:
   - Explore the interactive phylogenetic tree
   - Browse alphabetical list of families
   - Use search to find specific families
   - Access field identification guides
3. From the phylogenetic tree, user can click on a family to view detailed information
4. From family pages, user can:
   - View identification characteristics
   - See related families
   - Access field identification tips
   - Return to the tree view

## Responsive Design Considerations
- The website will be fully responsive for mobile, tablet, and desktop
- The phylogenetic tree will adapt to screen size:
  - Full interactive version for desktop
  - Simplified, scrollable version for mobile
- Images will resize appropriately for different devices
- Navigation will collapse to a hamburger menu on smaller screens
