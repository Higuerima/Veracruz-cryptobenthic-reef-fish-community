# Veracruz-cryptobenthic-reef-fish-community

For Crptos.VER.DataFrame.csv:
#Rows
Each row represents a fish individual

#Columns
Date: Date of collection
Year: Year of collection
Month: Month of collection
Country: Country of collection
Reef_name: Name of the reef where the collection happened
Site_name: Given name to the site where the collection happened
Reef_zone: Exposed (receiving direct wave action) or Protected (low wave action)
N: Coordinates 
W: Coordinates
Depth_(m): Depth to which the collection happened
Methodology: CryptoStation (Enclosed clove:oil station), target to sample the cryptobenthic reef fish community, or Roving Quadrant, which refers to the collection of cryptobenthic reef fishes on a microhabitat scale.
Transect: CS if cryptostations or Q if roving quadrants were performed. 
Microhabitat_No: Habitat ID number where a fish was captured.
Microhabitat_label: Individual identification of a microhabitat, if NA, then the fish was captured on a cryptostation. 
Fish_tag_ID: Individual code for a fish individual. 
Family: Taxonomy
Genus: Taxonomy
Species: Taxonomy
Hummid_weight_(gr): Fish total humid weight in gr
TL(mm): Fish total length in mm
Park_region: The Veracruz Reef System is divided by the Jamapa River plume into two regions, North and South.


For Microh_DataFrame.csv:
#Rows
Each row represents an individual microhabitat sampled

#Columns
Date: Date of collection
Year: Year of collection
Month: Month of collection
Country: Country of collection
Reef_name: Name of the reef where the collection happened
Site_name: Given name to the site where the collection happened
Reef_zone: Exposed (receiving direct wave action) or Protected (low wave action)
N: Coordinates 
W: Coordinates
Methodology: CryptoStation (Enclosed clove:oil station), target to sample the cryptobenthic reef fish community, or Roving Quadrant, which refers to the collection of cryptobenthic reef fishes on a microhabitat scale.
Transect: CS if cryptostations or Q if roving quadrants were performed. 
Microhabitat_No: Habitat ID number where a fish was captured.
Microhabitat_label: Individual identification of a microhabitat, if NA, then the fish was captured on a cryptostation.
Field_component_ID: Component ID in the field while diving.
Group_Classification(ImageID): Component in which a microhabitat was grouped after CORALNET ID.
Fish_catched: Number of fish cached in a microhabitat.


For annotations.csv:
#Columns
Name: Name of the photo, example "2023.ENMExpuesto2.T2Q10.JPG" 2023 + year, ENMExpuesto= name of the site, T2= Transect number, Q10= Number of photoquadrant
Site_name: Given name to the site where the phototransect happened
Transect:
Row: Photo coordinate
Column: Photo coordinate
Label: benthic component label ID

For metadata.csv:
#Columns
Name: Name of the photo, example "2023.ENMExpuesto2.T2Q10.JPG" 2023 + year, ENMExpuesto= name of the site, T2= Transect number, Q10= Number of photoquadrant
Localidad: Veracruz Reef System
Site_name: Given name to the site where the phototransect happened
Transect: Number of phototransect

For percentage_covers_abbreviations.csv:
#Columns
Image ID: Image ID given by CORALNET
Image name: Name of the photo, example "2023.ENMExpuesto2.T2Q10.JPG" 2023 + year, ENMExpuesto= name of the site, T2= Transect number, Q10= Number of photoquadrant.
Annotation status: CORALNET's confirmation that an annotation was successfully ID.
Points: Random points by photo.
Next columns: Abbreviations of each component ID in the Veracruz CORALNET project.







