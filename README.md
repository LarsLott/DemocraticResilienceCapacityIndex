# Democratic Resilience in the Twenty-First Century. Search for an Analytical Framework and Explorative Analysis #

This repository makes the Democratic Resilience Capacity (DRC) Index available for future research and use. Please also see the introductory paper published at Political Studies 

Croissant, Aurel & Lott, Lars, (2025). Democratic Resilience in the Twenty-First Century. Search for an analytical framework and explorative analysis. Political Studies. doi:10.1177/00323217251345779.

## Codebook ##

### Democratic Resilience Capacity (DRC) Index 

Additional versions: _codelow, _codehigh, _sd
Questions: To what extent is democratic resilience capacity achieved?
Scale: Interval, from low to high (0-1)
Source: inst_dim polpar_dim civsoc_dim, polcom_dim
Aggregation: The Democratic Resilience Capacity Index is formed by taking the average of, on the one hand, the indices measuring the macro-institutional dimensions (inst_dim), the political actors’ dimensions (polpar_dim), the civic culture and civil society dimensions (civsoc_dim), and the political community of citizens dimensions (polcom_dim), and, on the other hand, the four-way multiplicative interaction between those indices. The question of whether to use multiplicative or additive indices has been debated in democracy measurement studies for decades, without conclusive results (see Coppedge et al. 2020, 97-101; Goertz 2006: 111-15; Treier and Jackman 2008; Przeworski et al. 2000; Munck 2009; Bollen 1980; Coppedge and Reinicke 1990). Since both the necessary conditions and the substitutable logic have reasoned support, and since both have evidently the virtue of discriminating at different ends of the spectrum, we use the average between the two as our preferred solution to the aggregation of a complex concept, such as resilience capacity. The index is aggregated using this formula:

DRC Index = 0.5 * aDRC + 0.5 * mDRC 
=0.5 * (1/4 * inst_dim + 1/4 * polpar_dim +1/4 * civsoc_dim + 1/4 * polcom_dim) + 0.5* (inst_dim * polpar_dim * civsoc_dim * polcom_dim)

Citation: Croissant and Lott (2025) (see suggested citation in the main document)
Years: 2000-2023

### Additive Democratic Resilience Capacity (aDRC) Index 

Additional versions: _codelow, _codehigh, _sd
Questions: To what extent is democratic resilience capacity achieved?
Scale: Interval, from low to high (0-1)
Source: inst_dim polpar_dim civsoc_dim, polcom_dim
Aggregation: The Additive Democratic Resilience Capacity Index is formed by taking the average of the average of the indices measuring the macro-institutional dimensions (inst_dim), the political actors’ dimensions (polpar_dim), the civic culture and civil society dimensions (civsoc_dim), and the political community of citizens dimensions (polcom_dim). The index is aggregated using this formula:

aDRC = 1/4 * inst_dim + 1/4 * polpar_dim +1/4 * civsoc_dim + 1/4 * polcom_dim 

Citation: Croissant and Lott (2025) (see suggested citation in the main document)
Years: 2000-2023

### Multiplicative Democratic Resilience Capacity (mDRC) Index 

Additional versions: _codelow, _codehigh, _sd
Questions: To what extent is democratic resilience capacity achieved?
Scale: Interval, from low to high (0-1)
Source: inst_dim polpar_dim civsoc_dim, polcom_dim
Aggregation: The Multiplicative Democratic Resilience Capacity Index is formed by the four-way multiplicative interaction between the indices measuring the macro-institutional dimensions (inst_dim), the political actors’ dimensions (polpar_dim), the civic culture and civil society dimensions (civsoc_dim), and the political community of citizens dimensions (polcom_dim). The index is aggregated using this formula:

mDRC = inst_dim * polpar_dim * civsoc_dim * polcom_dim

Citation: Croissant and Lott (2025) (see suggested citation in the main document)
Years: 2000-2023

### Macro-institutional level dimension (inst_dim)

Additional versions: _codelow, _codehigh, _sd
Questions: The macro-institutional level concerns core procedural rules and institutions which are relevant for the survival and democratic quality of the regime and asks to what extent these are achieved?
Scale: Interval, from low to high (0-1)
Source: democracy_stock v2juhcind v2juncind v2juhccomp v2jucomp v2exrescon v2lgotovst v2lginvstp v2lgqstexp (all from V-Dem v14)
Aggregation: The index is formed by taking the point estimates from a Bayesian factor analysis
model of the indicators for democratic stock (democracy_stock), and the indicators from the horizontal accountability index (Lührmann et al. 2020), namely high court independence (v2juncind), Lower court independence (v2juncind), Compliance with high court (v2juhccomp), Compliance with judiciary (v2jucomp), Executive respects constitution (v2exrescon), Executive oversight (v2lgotovst), Legislature investigates in practice (v2lginvstp), and legislature questions officials in practice (v2lgqstexp).  

### Political actors’ dimension (polpar_dim)

Additional versions: _codelow, _codehigh, _sd
Questions: At the level of relevant political actors, political parties play a key role. We identify three party-related variable and ask to what extent political actors, i.e., political parties, are committed to democratic institutions and processes. 
Scale: Interval, from low to high (0-1)
Source: anti_pluralist_party_index_rev (from V-Party v2) v2cacamps_osp_rev v2caviol_osp_rev (from V-Dem v14)
Aggregation: The index is formed by taking the point estimates from a Bayesian factor analysis
model of the Index for Anti-Pluralist-Party (anti_pluralist_party_index_rev), and the indicators for political polarization (v2cacamps_osp_rev), and political violence (v2caviol_osp_rev). The three respective indicators are rescaled to values from low commitment to democracy to strong commitment to democracy indicated by the _rev at the end of the variables. Thus, the higher the Anti-Pluralist-Party Index, the stronger the commitment to democracy, and the higher the indicators on political polarization and political violence, the lower the levels of polarization and the lower the levels of political violence, respectively.
Citation: Croissant and Lott (2025) (see suggested citation in the main document)
Years: 2000-2023

### Civil society and civic culture dimension (civsoc_dim)

Additional versions: _codelow, _codehigh, _sd
Questions: The civil society and civic culture dimensions treats civil society (measured by the Core Civil Society Index) and asks about the dispersion in the distribution of power resources (measured by the Equal Access Index) as this implies that the resilience capacity of a democracy is stronger when social groups “enjoy equal de facto capabilities to participate, to serve in positions of political power, to put issues on the agenda, and to influence policymaking” (Coppedge, et al. 2024, 59). The civil society and civic culture dimension asks to what extent are robust civil society and a broader distribution of power resources is achieved?
Scale: Interval, from low to high (0-1)
Source: v2pepwrgen v2pepwrses v2pepwrsoc v2cseeorgs v2csprtcpt v2csreprss (all from V-Dem v14)
Aggregation: The index is formed by taking the point estimates from a Bayesian factor analysis
model of the indicators for Power distributed by gender (v2pepwrgen), Power distributed by socio-economic position (v2pepwrses), Power distributed by social group (v2pepwrsoc), CSO entry and exit (v2cseeorgs), CSO participatory environment (v2csprtcpt), CSO repression (v2csreprss).  

### Political community dimension (polcom_dim)

Additional versions: _codelow, _codehigh, _sd
Questions: The political community dimension asks to what extent members of a political community are attached to “democratic ideals (…), in spite of hostility from the officially prescribed values and norms and apparent indifference from many elements in society” (Burnell and Calvert, 1999, p. 4, as cited in Merkel and Lührmann, 2021). The greater the proportion of citizens that shares this identity the easier it is for democracy to function and persist.
Scale: Interval, from low to high (0-1)
Source: parl gov police leg (all from Valgarðsson et al. 2025) Satis (from Claassen 2020)
Aggregation: The index is formed by taking the point estimates from a Bayesian factor analysis
model of the indicators for Trust in representative institutions: parliament (parl), Trust in representative institutions: government (gov), Trust in order institutions: police (police), Trust in order institutions: legal system (leg), Satisfaction with Democracy (Satis).  







