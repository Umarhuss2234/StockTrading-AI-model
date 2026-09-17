# StockTrading-AI-model
This repo is more off a place holder rather then actually containing a lot off this projects code. I trained Claude AI to constantly scrape the internet, stock market history and predictions to make trades. 

I first got the AI to trade just over prompt inputs. It didn't have access to any from off account or any actual trading platform. I would monitor what the AI is saying for over a week and see if we made a loss or made a profit. Then I moved the AI to trading via an EC2 instant on Demo accounts to do paper trading. After I saw that the AI was doing relatively well, I moved it onto a real trading account to start making real trades.

The EC2 instance was created and monitored manually. However I do have a terraform file in this repo that has the configurations for the EC2 instant.
