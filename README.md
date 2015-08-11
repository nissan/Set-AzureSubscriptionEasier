# Set-AzureSubscriptionEasier
Allows a user to sign in to Azure and change the subscription they are currently logged in to more easily.
The problem is that currently with Set-AzureSubscription the name of the subscription must be known. To get a list of the subscriptions there's a command that has to be run separately.
This simple script allows an Azure administrator who may have more than one Azure account and then more than one Azure subscription with each account to firstly choose to log in to a different account or stay with the current Azure account signed in, view the current subscription that has currently been set and then if they choose see a list of available subscriptions with the "SubscriptionName" parameter needed to change the current subscription to that preferred subscription.

Nothing too big and beautiful, but it does save a few moments, and can be farmed out as a task to other junior administrators without requiring them to learn all the Powershell syntax immediately.
