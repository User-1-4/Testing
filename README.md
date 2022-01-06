# Testing
{
    "type": "AdaptiveCard",
    "body": [
        {
            "type": "Container",
            "minHeight": "150px",
            "backgroundImage": "https://adaptivecards.io/content/AlkiBeach.jpg",
            "items": [
                {
                    "type": "TextBlock",
                    "text": "What a beautiful background"
                }
            ]
        },
        {
            "type": "TextBlock",
            "text": "They can even repeat a bunch of different ways..."
        },
        {
            "type": "Container",
            "minHeight": "100px",
            "backgroundImage": {
                "url": "https://adaptivecards.io/content/uparrow.png",
                "fillMode": "Repeat"
            },
            "items": []
        },
        {
            "type": "Container",
            "backgroundImage": {
                "url": "https://adaptivecards.io/content/uparrow.png",
                "fillMode": "RepeatHorizontally",
                "verticalAlignment": "Center"
            },
            "items": []
        },
        {
            "type": "Container",
            "minHeight": "100px",
            "backgroundImage": {
                "url": "https://adaptivecards.io/content/uparrow.png",
                "fillMode": "RepeatVertically",
                "horizontalAlignment": "Center"
            },
            "items": []
        }
    ],
    "$schema": "http://adaptivecards.io/schemas/adaptive-card.json",
    "version": "1.2"
}
