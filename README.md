# Supplementary Materials for the article draft “Author gender and text characteristics in contemporary Swedish fiction”

**Mats Dahllöf, Uppsala University, 2022-11-11**

`fmcorp.csv`: A csv listing of the works in the corpus along with relevant metadata.

## Tables over text properties clearly associated with gender

Tables over text property measures which were clearly associated with gender differences, i.e. met our size effect and significance criterion.

[`estabF_gram.csv`](estabF_gram.csv): Grammar-based measures higher for female authors (Table 3 in the article is an excerpt).

[`estabM_gram.csv`](estabM_gram.csv): Grammar-based measures higher for male authors (Table 4).

[`estabF_bring.csv`](estabF_bring.csv): Thesaurus-based measures higher for female authors (Table 5).

[`estabM_bring.csv`](estabM_bring.csv): Thesaurus-based measures higher for male authors (Table 6).

[`estabF_graph.csv`](estabF_graph.csv): Measures based on graphic words higher for female authors (Table 7).

[`estabM_graph.csv`](estabM_graph.csv): Measures based on graphic words higher for male authors (Table 8). 

These files contain the following columns:

`measure`: The measure, code derived from the tagging or Bring thesurus, or graphical word.

`transl`: The measure in more standard terminology or grapic word translated into English. 

`iclass`: How the measure is categorized in the discussion. 	

`ps_a`: Probability of superiority when all authors are compared. 	

`ps_b`: Probability of superiority when all books are compared. 	 	

`ps_Cb`: Probability of superiority when all crime books are compared. 	

`ps_Ob`: Probability of superiority when all non-crime books are compared. 

`aMd0`: Median value per authors of the first gender in the comparison.	Relative frequency as parts per million.

`aMd1`: Median value per authors of the second gender in the comparison.	

`p_a`, `p_b`, `p_Cb`, and `p_Ob`: p values for cases as above. 

`d_a`, `d_b,` `d_Cb`, and `d_Ob`: Cohen's d for cases as above. 

## Tables over graphic words behind grammatical and Bring class measures

Tables over which graphic words generated most of the weight (added over the whole corpus) for the grammatical and Bring thesaurus class measures.
Columns for measure and top 15 graph words with total weight.

[`graph_gram.csv`](graph_gram.csv): The graphic words behind the grammatical text propery measures.

[`graph_bring.csv`](graph_bring.csv): The graphic words behind the Bring thesaurus class text propery measures.

## “Follow-up inspections”

Read these as the `estabF_gram.csv` file. Numbers are reported from the female to male comparison point of view.

[`fu_number.csv`](fu_number.csv): for Section 4.1 on number in determiners, nouns, pronouns, adjectives, past participles.

[`fu_degree.csv`](fu_degree.csv): for Section 4.1 on degree inflection in adjectives and adverbs.

[`fu_pronouns.csv`](fu_pronouns.csv): for Section 5 on same-gender gendered pronoun use.







