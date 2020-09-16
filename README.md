# fedex-us-das

Fedex Delivery Area Surcharge US ZIP Codes

The JSON file is created from the Delivery Area Surcharge ZIP Codes List

Current version is from the January 6, 2020 PDF https://www.fedex.com/content/dam/fedex/us-united-states/services/DAS_Contiguous_Extended_Alaska_Hawaii_2020.pdf

## Objectives

1. Preserve leading zeros
1. Expand ranges, so `04344-04347` actually yields 4 items: `04344`, `04345`, `04346` and `04347`
1. Key by surcharge types `contiguous_us`, `contiguous_us_extended`, `alaska`, `hawaii`, `intra_hawaii`