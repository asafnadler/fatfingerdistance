# fatfingerdistance
Fat Finger Distance is an edit distance metric designed to detect mistyping over a given grammer.
It is inspired by T.Moore and B. Edelman "Measuring the perpetrators and funders of typosquatting"

Fat finger distance is in fact Levenshtein distance with euclidean distance over mismatches and a branch-and-bound approach to bound number of errors for optimization over a large vocabulary.
