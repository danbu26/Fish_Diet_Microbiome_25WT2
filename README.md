# Fish_Diet_Microbiome_25WT2
# Code for filtering: metadata_diet_types_mutated = metadata_diet_types |> mutate(Diet_car_omn = if_else(str_detect(Diet,regex( "algae|plant|seaweed|planktonon|opportunistic|coelenterates", ignore_case = TRUE)), "Omnivores", "Carnivores"), .after = Diet)
# figure S1: alpha & beta diversity
# table S2: indicator
# figure S2: taxonomy_boxplot
# Differential abundance-massalin table S1
# Table S3: Picrust 2
# Figure 2: beta diversity vs alpha diversity (permanova: beta diversity ~ fish species + diet)
