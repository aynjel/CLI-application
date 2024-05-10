# CLI APPLICATION

## Description

This is a command line application using Node.js.

## Run in the terminal

#### Get and display the entire list of contacts in the form of a table (console.table)

![list command](https://d960fn7fik8w3.cloudfront.net/ms_642432/WoSqz6XYVoqCuaVfwzJHviFGAokiYA/list.jpg?Expires=1715362200&Signature=GMMxQPMYVMOW~p0ynau6Se5zfUVAXZAGAROp9EP2lRKh0uuzzc3DruHz5fWFJ7-WwAOJNX0Cgo3zbd7L9I-BDE3kydDx1yXlnrI8KwDRqtlBb~d5l2qN0lPgQ1wO1ndvfaJWdZDQXm7qmTgjr2h7ktg0BOosFpMVHGFbKynZa8BA5Ndi900wrTvc8YlVbjgYk-6IP3DigDs7SS6UVKLqa~zZSUTQqgDmVPVfJO2zgBbwJLGGhWCcSleHiRNNq5qi9O18lZVVYsMvSdP2KWvWBI2yEKRuvlih5IMB2aHhoHTESiVj2W5NGJ9MqQ-qzO8zgdJn8FeTFrszO2PWBnp1~A__&Key-Pair-Id=APKAJBCGYQYURKHBGCOA)

```
node index.js --action list
```

#### Get and display a contact by id

![get command](https://d960fn7fik8w3.cloudfront.net/ms_642432/egfwFeX5vUZXOSSYMsM1zc8oqeDlvw/get.jpg?Expires=1715362200&Signature=UtOjxYs9Qq6Jq62cDXpPJj5AOtovnhmOWuMdzND3p2ejYl-MrQmqTYndMoAApusWHI1dkR1TX-OBAYi8E~UidRme240x1P7--2Sf1xfkf8cXbiNNtRwUEcmw7SMOxSORti-ZdZoI3~KS3JPFPjdJ8h0xZuFggZtb8Lgps1XdNf0buSjIjPyr1jaJg57FaEvAeHVet8siDCunqbzcQeAbBd-C-NqrVXPnR96CBasSz-DpmG9l-EyA6tW0Y1~JqkkpJ7EQO2ZE5abPGGoPrHAcEADTQ9DYq5aF9KmaDCuicB7OHmuixgtUeXZ36KzMF6u7OJK9KOJdgaAkW7SWQ-uY6Q__&Key-Pair-Id=APKAJBCGYQYURKHBGCOA)

```
node index.js --action get --id 5
```

#### Add a new contact

![add command](https://d960fn7fik8w3.cloudfront.net/ms_642432/wPkAL0p4V9PIhEND7thk6gE0wVXMzZ/add.jpg?Expires=1715362200&Signature=PuZOw72p0-UjUbO7ptfKtKvGWTrjWwb6LO0QUFimHdezUTFJ1xMquAm-MiIkc9Y-43XvPPstutbVcXaLQ4sF0Y2WRwYx6rRV6A8nga-CXp0Vr75J1VB0otGJPtQjQgC2eZQWAODRaOkKcFlV3a5EOEvs84EvG0bcYkP5-itCcLTjWJfsBGeV2MUhUc91N68qbJr-GQLLqwP~3P~0~GvGlopJPmdgn0WIqF1YLul3SeQC1mk-OHnoXk0KIeJ6f19QPIL4dUFDEqA59UsX9Oj5NmBdxoVpRoKLZS2lXeswn63Ll0~zk6-PU3-NzfkHG3O5aMvnt3wWaf2tAABqYBuGcA__&Key-Pair-Id=APKAJBCGYQYURKHBGCOA)

```
node index.js --action add --name Mango --email

```

#### Remove a contact by id

![remove command](https://d960fn7fik8w3.cloudfront.net/ms_642432/9yZCBusaP2x476EHsDzeccvuyaAmG8/remove.jpg?Expires=1715362200&Signature=F9zzvIDDGMnGmtnUxHoC-6oKcHqPJGr7EA5AIynJp5E5Hz~acZf35C5YkUfktwH3rlnI~TLWXeyTzTnVGqbX2HBFplq0tKMUJydiRQVAdUP4QNxZKiyWvTEipvGKfgqVRreT5JgYMLtt~w-NYjUA8OARtzVhO-y95nzxcvySKghJtFehcfCmVoQhMTAYmreMmcwZUEYG01KFRm-EPyp2zaODKLmstzQdAvncvh4Gva7yEJ2zMTQFWrnomTPYLQnhW-l-XzT7YtHT9EWLPUGldwaXTwYdl5cvJ~tTfh8JQlpWuRhEAkcd9Ux36r9L9FyUmwyY-SOjJIzcvbH~kz8LJw__&Key-Pair-Id=APKAJBCGYQYURKHBGCOA)

```
node index.js --action remove --id 3
```
