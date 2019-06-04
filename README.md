# k8
{
    "interactionModel": {
        "languageModel": {
            "invocationName": "geoguesser",
            "intents": [
                {
                    "name": "AMAZON.FallbackIntent",
                    "samples": []
                },
                {
                    "name": "AMAZON.CancelIntent",
                    "samples": []
                },
                {
                    "name": "AMAZON.HelpIntent",
                    "samples": []
                },
                {
                    "name": "AMAZON.StopIntent",
                    "samples": []
                },
                {
                    "name": "AMAZON.NavigateHomeIntent",
                    "samples": []
                },
                {
                    "name": "PeruIntent",
                    "slots": [
                        {
                            "name": "firstCountry",
                            "type": "AMAZON.Color"
                        }
                    ],
                    "samples": [
                        "the first country is {firstCountry}"
                    ]
                },
                {
                    "name": "SriLankaIntent",
                    "slots": [
                        {
                            "name": "secondCountry",
                            "type": "AMAZON.Color"
                        }
                    ],
                    "samples": [
                        "the second country is {secondCountry}"
                    ]
                },
                {
                    "name": "LebanonIntent",
                    "slots": [
                        {
                            "name": "thirdcountry",
                            "type": "AMAZON.Color"
                        }
                    ],
                    "samples": [
                        "the third country is {thirdcountry}"
                    ]
                }
            ],
            "types": []
        }
    }
}
