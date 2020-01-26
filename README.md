# replace_sumif_countifs_avgifs
replace_sumif_countifs_avgifs


# Ussualy in Excel to summarize a table that includes the average, counts or sums for aggregated products we build 
# an extra table in which we do sumifs, countifs , avgifs.

# in pandas it is much easier. just group by the product and apply sum function or countfunction, in a separate dataframe
# using the original df for calculations.
