## How to Remove rows with same column value in R
<ls>Here we are removing rows which have same value in the column 'ListingKey'</ls>

pf <-pf[!duplicated(pf[c('ListingKey')]),]
