#📝 PAN Number Validation Project

This project focuses on data cleaning and validation of Permanent Account Numbers (PAN) of Indian nationals. The objective is to ensure that each PAN number adheres to the official format and is categorized as either Valid or Invalid.

The dataset used is provided in:
📂 PAN Number Validation Dataset.xlsx

# Objectives

-Clean and preprocess PAN number data.

-Validate PAN numbers against official format rules.

-Categorize PAN numbers as Valid or Invalid.

-Generate a summary report of results.

# Data Cleaning & Preprocessing

-Handle Missing Data

 -Identify and handle missing PAN values (remove or impute depending on context).

-Remove Duplicates

 -Ensure all PAN numbers are unique.

-Trim Whitespaces

 -Remove leading and trailing spaces.

-Correct Letter Case

 -Convert all PAN numbers to uppercase.

# PAN Format Validation Rules

 -A valid PAN number must:

 -Be exactly 10 characters long.

 -Follow the format: AAAAA1234A

 -First 5 characters: alphabetic (A–Z)

 -No adjacent repeating letters (e.g., AABCD ❌, AXBCD ✅)

 -Not a sequential string (e.g., ABCDE, BCDEF ❌, ABCDX ✅)

 -Next 4 characters: numeric (0–9)

 -No adjacent repeating digits (e.g., 1123 ❌, 1923 ✅)

 -Not sequential (e.g., 1234, 2345 ❌)

 -Last 1 character: alphabetic (A–Z)

✅ Example of a valid PAN: AHGVE1276F

# Categorization

 -Valid PAN → Meets all format rules.

 -Invalid PAN → Fails format rules, incomplete, or contains invalid characters.

# Tasks

-Validate PAN numbers using the rules above.

-Categorize into:

 -Valid PAN

 -Invalid PAN

# Generate a summary report including:

 -Total records processed

 -Total valid PANs

 -Total invalid PANs

 -Total missing or incomplete PANs (if any)
