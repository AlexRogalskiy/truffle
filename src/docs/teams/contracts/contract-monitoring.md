---
title: Teams | Contract Monitoring
layout: docs.hbs
---
# Contract Monitoring

We can monitor any contract that is deployed to a network and has a Truffle artifact file. Monitoring provides realtime data for a deployed contract including: transactions (both successful and failed), events, and the contract's balance. It also displays useful information such as the address and creation transaction hash.

## Adding Contracts for Monitoring

To start monitoring, click the <span class="inline-menu-item"><i class="fas fa-table"></i>DATA</span> link in the sidebar and then the <span class="inline-button">UPLOAD ARTIFACT FILES</span> button.

![Truffle Teams DATA view](/img/docs/teams/add-contract-01.png)

From there your operating system's file picker will open. Navigate to your project's contract build folder and select the artifacts you wish to upload. You can select more than one at at time.

![Truffle Teams DATA view](/img/docs/teams/add-contract-02.png)

Select the network where this contract is deployed--we'll attempt to fill in the address from the artifact file. If the address does not auto-fill, but you're sure the correct network is selected, you may need to manually add it. Click the <span class="inline-button">NEXT >></span> button to once you've confirmed all the data is correct.

![Truffle Teams DATA view](/img/docs/teams/add-contract-03.png)

Truffle Teams will then verify that the contracts exist on the given network at the given addresses. If there are errors shown in this dialog the contracts either exist on a different network or incorrect addresses were given in the last step. Click the <span class="inline-button">CONFIRM >></span> button to begin uploading the artifacts and hooking up monitoring.

![Truffle Teams DATA view](/img/docs/teams/add-contract-04.png)

Once the upload is successful and monitoring has begun, you'll be redirected to the `DATA` page. From there you can click an individual contract to see more details including successful transactions, failed transactions, and events live.

<p class="alert alert-info">
<strong>Note</strong>: Monitoring begins once the contract is added to Truffle Teams and does not currently include historical data from before that point.
</p>

![Truffle Teams DATA view](/img/docs/teams/add-contract-06.png)

![Truffle Teams DATA view](/img/docs/teams/add-contract-07.png "Monitoring detail page showing details, transactions, and events.")
