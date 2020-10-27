# OpeningLeadCheats
Building AI course project - an idea for an AI project (analyze opening leads in bridge and detect anomalies)

# Project Title

Building AI course project - Opening Lead Cheaters in Bridge

## Summary

This project is about building an AI system to assess opening leads in bridge. The learning data set is mined from online bridge servers and should include hands from high level play. The model should be used to detect anomalies in opening lead selections. The anomalies could be fed to a double dummy solver to identify if the anomalies lead to better or worse outcomes. In case the average of the anomalies are better than break-even between better and worse outcomes, a further investigation is warranted. The purpose of the project is to create a fast tool to detect potential cheats.

## Background

Since the COVID-19 outbreak, face to face (f2f) bridge practically ceased to exist. The tournaments moved to online platforms, nost notably to the BBO (Bridgebase Online, www.bridgebase.com)

Online bridge cannot have the same controls as f2f bridge and multiple cheating cases were detected and even more were suspected. Nicolas Hammond has mined a hand database and has used double dummy solver to assess the outcome of opening leads. The double dummy analysis brings up better than average opening leaders and can also suggest that the top opening leaders are too good to be true. The difference with the NH solution is to recognize those opening leads, which are anomalies.

In addition to the cheat weeding purpose, the solution can be utilized for understanding how top players decide their opening leads.

## How is it used?

The initial use case is for an analyst to train and test the AI using stored data from f2f tournaments before COVID-19; the training data should exclude opeing leads made by already convicted cheats.

Describe the process of using the solution. In what kind situations is the solution needed (environment, time, etc.)? Who are the users, what kinds of needs should be taken into account?

Once the model is trained, an analyst can use the AI to test opening lead data from the post COVID-19 tournaments.

## Data sources and AI methods

The data sources are the vugraph archives of online bridge servers. The data inlcudes the hands, the auction, and the full play, including the opening lead made.
As part of the project, the data needs to be harvested from the archives. During the harvesting, hands played by convicted cheats should be excluded.

## Challenges

The project does not solve if someone is cheating or not. It might weed out a set of pairs, among whom cheating is significantly more probable than among the whole population. Manual analyst work will be required.

## What next?

Most likely the Nicolas Hammond database will remain the de-facto tool to identify players suspectible for cheating.
