### gpt-3.5-turbo API, Javascript demo

```javascript
try {
    const response = await fetch("https://api.openai.com/v1/chat/completions", {
        method: "POST",
        headers: {
            Authorization: `Bearer ${API_KEY}`,
            "Content-Type": "application/json"
        },
        body: JSON.stringify({
            model: "gpt-3.5-turbo",
            temperature: 0.5,
            messages: [{ "role": "user", "content": userInput }]
        })
    });
    const data = await response.json();
    console.log(data);

    // Display the response
    const responseText = data.choices[0].message.content;
} catch (error) {
    console.error("Error fetching data: ", error);
}
```

### Image generator API, Javascript demo

```javascript
try {
    const response = await fetch("https://api.openai.com/v1/images/generations", {
        method: "POST",
        headers: {
            Authorization: `Bearer ${API_KEY}`,
            "Content-Type": "application/json"
        },
        body: JSON.stringify({
            prompt: prompt,
            n: 1,
            size: "1024x1024"
        })
    });
    const data = await response.json();
    console.log(data);
    data?.data.forEach(imageObject => {
        const ImageContainer = document.createElement('div');
        const imageElement = document.createElement('img');
        imageElement.setAttribute('src', imageObject.url);
        ImageContainer.append(imageElement);
        imageSection.append(ImageContainer);
    });
} catch (error) {
        console.error("Error fetching data: ", error);
}
```