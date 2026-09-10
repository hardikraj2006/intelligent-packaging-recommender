# Intelligent Packaging Recommender System

An AI-powered intelligent packaging recommendation application that suggests suitable packaging materials and specifications for different food commodities.

## Features

- 🤖 **AI-Based Recommendations**: Machine learning-powered packaging recommendations
- 📊 **Comprehensive Analysis**: Analyzes food properties (moisture, pH, respiration rate, etc.)
- 📦 **Material Database**: Extensive packaging materials library
- 🌡️ **Environmental Conditions**: Considers storage temperature, humidity, and transportation
- 🥗 **Fresh Produce Support**: Special handling for fruits and vegetables with respiration rates
- 📈 **Shelf Life Prediction**: Estimates product shelf life
- ♻️ **Sustainability Analysis**: Eco-friendly packaging recommendations
- 💰 **Cost Optimization**: Balances quality with cost
- 📱 **Responsive Design**: Works on desktop and mobile devices

## System Components

### Recommended Packaging Outputs

- **Materials**: LDPE, HDPE, PET, Metalized Films, Aluminum Foil, Biodegradable Films
- **Specifications**:
  - Oxygen Transmission Rate (OTR)
  - Water Vapor Transmission Rate (WVTR)
  - Film Thickness
  - Sealability
  - Gas Permeability
  - Mechanical Strength
  - Modified Atmosphere Packaging (MAP) Suitability

## Tech Stack

- **Backend**: Python (Flask)
- **Frontend**: HTML5, CSS3, JavaScript
- **Machine Learning**: Scikit-learn
- **Database**: SQLite
- **Deployment**: Docker

## Installation

### Prerequisites

- Python 3.8+
- Git

### Setup

1. Clone the repository
```bash
git clone https://github.com/hardikraj2006/intelligent-packaging-recommender.git
cd intelligent-packaging-recommender
```

2. Install dependencies
```bash
pip install -r requirements.txt
```

3. Run the application
```bash
python app.py
```

4. Open in browser
```
http://localhost:5000
```

## Usage

1. Select commodity type (fruits, vegetables, grains, dairy, etc.)
2. Enter food properties (moisture, pH, oil content, etc.)
3. Specify storage conditions (temperature, humidity, duration)
4. Click "Get Recommendation"
5. View detailed packaging recommendations with specifications

## Project Structure

```
intelligent-packaging-recommender/
├── app.py                 # Main Flask application
├── requirements.txt       # Python dependencies
├── config.py             # Configuration settings
├── static/               # CSS, JavaScript, images
│   ├── css/
│   ├── js/
│   └── images/
├── templates/            # HTML templates
│   ├── base.html
│   ├── index.html
│   ├── recommendations.html
│   └── about.html
├── models/               # ML models and data
│   ├── recommender.py
│   └── materials_data.py
└── tests/                # Unit tests
    └── test_recommender.py
```

## Output Recommendations

The system provides:
- ✅ Best suited packaging materials
- ✅ Recommended OTR and WVTR values
- ✅ Suggested film thickness
- ✅ Barrier properties required
- ✅ Cost-effectiveness analysis
- ✅ Sustainability score
- ✅ Expected shelf life

## License

This project is licensed under the MIT License.

## Support

For issues and questions, please open an issue on GitHub.
