# Fish_Diet_Microbiome_25WT2
# Code for filtering: metadata_diet_types_mutated = metadata_diet_types |> mutate(Diet_car_omn = if_else(str_detect(Diet,regex( "algae|plant|seaweed|planktonon|opportunistic|coelenterates", ignore_case = TRUE)), "Omnivores", "Carnivores"), .after = Diet)
