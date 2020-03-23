# Large-scale ligand-based virtual screening for potential SARS-Cov-2 inhibitors using a deep neural network

Markus Hofmarcher, Andreas Mayr, Elisabeth Rumetshofer, Peter Ruch, Philipp Renz, Johannes Schimunek, Philipp Seidl, Andreu Vall, Michael Widrich, Sepp Hochreiter, Guenter Klambauer

Institute for Machine Learning & LIT AI Lab, Johannes Kepler University Linz, Austria


Due to the current severe acute respiratory syndrome coronavirus 2 (SARS-CoV-2) pandemic, there is an urgent need for novel therapies anddrugs. We conducted a large-scale virtual screening for small molecules that are potential CoV-2 inhibitors. To this end, we use a deep neural network, called ”ChemAI”, trained on more than 220M data points over 3.6M molecules from three public drug-discovery databases. This network is used to **screen and rank a billion molecules from the ZINC database** for favorable effects against SARS-CoV-2. We publish the 30,000 top-ranked compounds, which are easily accessible via ZINC, as a library for further screening with bioassays.

The list is available in csv format for automated processing and in Excel format for manual inspection.

Here are some examples of the top-ranked molecules:
![Examples](https://github.com/ml-jku/sars-cov-inhibitors-chemai/blob/master/examples.png?raw=true)
