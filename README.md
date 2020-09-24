# Overview of the Project
## Introduction

*rBCstats* is a capstone project, in partial fulfillment of the degree requirements for the Master of Data Science (MDS) at the University of British Columbia (UBC). This project was completed in partnership with the BC Stats, the provincial government of Brtish Columbia.

BC Stats is the provincial government's leader in statistical and economic research, information, and analysis. It helps business and institutions to increase overall performance by providing the information they need to make effective decisions. With the goal of shaping the future of education system in British Columbia, BC Stats undertakes large-scale surveys each year for public post-secondary institutions. For the Baccalaureate Graduates Survey (BGS), it asks former students who have graduated two or five years to provide feedback on employment outcomes, further education, education financing and student debt, and student satisfaction.

In this project, we are asked to discover thematic categories from the survey comment data. We developed a natural language processing dashboard that helps discover and interpret thematic categories from the survey comment. The dashboard provides various tools to allow better interpretation and refinement of topics and to leverage human efforts in identifying and analyzing potential topics. It includes operations to transform the corpus into a machine-readable format, to perform topic modeling, and visualizations to interpret and analyze topics at words and documents level. *rBCstats* is available as an open-source R package.

## Availablity of Data

The data provided is the 2-year-out graduate survey results in 2015 and 2016. These are gathered from UBC alumni who graduated in 2013 and 2014 and responded to the survey about their post-secondary outcomes. All data is provided as CSV files. For detail description of the data, please refer to the final report.

## Content of Dashboard

The *rBCstats* dashboard is modularized as an R Shiny app. It includes 4 main interfaces:

- **Datafile**: allows users to upload multiple survey data files, and select fields to include in the final analysis.
- **EDA**: provides some descriptive statistics about the corpus, and also allow user-specified pre-processing operations.
- **Topic modeling**: this is the main interface where users perform topic modeling using LDA, interpret the model, and download results.
- **LDAvis**: Interactive visualization for interpreting topic model.

The following documentation includes instructions on how to launch the dashboard through R and Docker.
Regarding the details usage of the dashboard, please refert to the below [User Guide](#documentation-and-report).

## Instruction for launching Dashboard
There are two main ways to launch the dashboard, please refer to the following instrutions:  

- [R package](./rBCstats/README.md)
- [Docker](docker-instruction.md)

## Documentation and Report
- **[Final report](./report/report.pdf)**: summary of the methodology and findings of this capstone project.
- **[User Guide](./rBCstats/inst/doc/user-guide.pdf)**: step-by-step instructions on how to use the dashboard.

## Acknowledgments

We are grateful to many of our colleagues at UBC. Especially, we are grateful to our capstone partner, Monkman, Martin, who came up with the project and provided useful feedback and support. We are also grateful to our mentor in the Master of Data Science program, Giulio Valentina Dalla Riva, whose advice was invaluable. Lastly, we are grateful to Hyeju Jang, Nasim Taba, and all our colleagues and instructors at the UBC MDS 2017 cohort who provided valuable feedback throughout our development process.

## License

This project is licensed under the *MIT License* and *Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International License*. [Details here](LINCESE.Md)

## Code of Conduct

Please note that this project is released with a [Contributor Code of Conduct](CODE_OF_CONDUCT.md).

## Contributing

Please refer to [CONTRIBUTING.md](CONTRIBUTING.md) for contributions.
