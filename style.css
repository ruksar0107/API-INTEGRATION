const apiKey = 'ababddef6b713a225b11c9a2fe2e8385'; // Your API key

function getWeather() {
  const city = encodeURIComponent(document.getElementById("cityInput").value.trim());
  const resultDiv = document.getElementById("weatherResult");

  if (!city) {
    resultDiv.innerHTML = `<p>Please enter a city name.</p>`;
    return;
  }

  const url = `https://api.openweathermap.org/data/2.5/weather?q=${city}&appid=${apiKey}&units=metric`;

  fetch(url)
    .then(response => {
      if (!response.ok) throw new Error("City not found");
      return response.json();
    })
    .then(data => {
      const weatherHTML = `
        <h2>${data.name}, ${data.sys.country}</h2>
        <p><strong>Temperature:</strong> ${data.main.temp} °C</p>
        <p><strong>Condition:</strong> ${data.weather[0].description}</p>
        <p><strong>Humidity:</strong> ${data.main.humidity}%</p>
        <p><strong>Wind speed:</strong> ${data.wind.speed} m/s</p>
      `;
      resultDiv.innerHTML = weatherHTML;
    })
    .catch(error => {
      resultDiv.innerHTML = `<p>${error.message}</p>`;
    });
}
