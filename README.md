# COVID-19 TRACKER

## [https://covid-tracker-wilden.web.app](https://covid-tracker-wilden.web.app)

### `npm start`

- Open [http://localhost:3000](http://localhost:3000) to view it in the browser.

# Create React Project

- `$ npx create-react-app .`
- Bersihin file2 dan program2 yg tidak terpakai

# Setup Firebase Project

1. Create Project in Firebase with name `covid-tracker-wilden`
2. Klik WebApp Icon
3. Create website name for the project
4. Install firebase-tools `$ npm install -g firebase-tools`
5. Login to firebase `$ firebase login`

# Install Material UI

1. Open [https://material-ui.com/getting-started/installation/](https://material-ui.com/getting-started/installation/)
2. Install material-ui `$ npm install @material-ui/core`

# Disease API, Covid-19 API

1. Open [https://disease.sh/](https://disease.sh/)
2. Click `Docs` Button
3. Click GET button on countries <br/>
   `https://disease.sh/v3/covid-19/countries`

# Install ChartJS 2

1. Goto [https://www.chartjs.org/](https://www.chartjs.org/)
2. Install
   `$ npm i react-chartjs-2 chart.js`
3. Baca baca disini [https://www.chartjs.org/docs/latest/charts/line.html](https://www.chartjs.org/docs/latest/charts/line.html) bagian Point[]
4. Install numeral
   `$ npm i numeral`

# Install for Map

1. Install<br/>
   `$ npm i react-leaflet`
   atau
   `$ npm install react-leaflet leaflet`

# Deploy to Firebase

1. Install firebase tools<br/>
   `$ npm install -g firebase-tools`
2. Firebase Init<br/>
   `$ firebase init`

- Are you ready to procees?<br/>
  `Jawab Y`
- Pilih Hosting: Configure and deploy Firebase Hosting sites
- What do you want to use as your public directory?<br/>
  `(awalnya public ganti jadi build)`
- Configure as a single-page app (rewrite all urls to /index.html)? (y/N)<br/>
  `jawab YES aja`
- `$ npm run build`
- `$ firebase deploy`
- Cara cepat `$ npm run build && firebase deploy`
