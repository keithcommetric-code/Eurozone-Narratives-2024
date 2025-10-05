# Bulgarian Eurozone Adoption Media Narratives Dataset (2022-2023)

## 📋 Overview

This dataset contains analyzed media content related to Bulgaria's potential adoption of the Euro currency, covering the period from July 2022 to July 2023. The data captures various narratives, sentiments, and arguments from Bulgarian media sources regarding Eurozone entry.

## 🎯 Purpose

To provide researchers, analysts, and policymakers with structured data on media discourse surrounding Bulgaria's Euro adoption process, including:
- Sentiment analysis of media coverage
- Key arguments and narratives from different stakeholders
- Media outlet positioning and coverage patterns
- Public discourse analysis

## 📊 Dataset Description

### File Information
- **Filename**: `Anon Eurozone Narratives Bulgaria 2024.xlsx`
- **Sheet Name**: `Cogent-Euro-Referendum-Bulgaria`
- **Time Period**: July 2022 - July 2023
- **Records**: 82 media items
- **Language**: Bulgarian (content), Metadata in English

### Key Columns

| Column Category | Examples | Description |
|----------------|----------|-------------|
| **Identification** | `Post ID`, `Title` | Unique identifiers and anonymized titles |
| **Metadata** | `PublishDate`, `Publication`, `Language` | Publication details |
| **Analysis** | `Sentiment`, `Relevance`, `SentimentId` | Coded analysis (-2 to +2 scale) |
| **Content** | `Message1` to `Message7.58` | Thematic content and arguments |
| **Actors** | `Spokesperson1-5` | Anonymized stakeholder categories |
| **Engagement** | `cc:Comments`, `cc:Likes`, `cc:Shares` | Social media metrics |

## 🔒 Anonymization

The dataset has been thoroughly anonymized to protect sources and maintain privacy:

- ✅ **Media outlets** replaced with generic identifiers
- ✅ **Journalists/Reporters** anonymized
- ✅ **Public figures** replaced with role-based identifiers
- ✅ **Specific details** generalized where necessary
- ✅ **Original titles** replaced with sequential identifiers

## 🏷️ Key Variables

### Sentiment Coding
- `+2`: Strongly Positive
- `+1`: Positive  
- `0`: Neutral/Balanced
- `-1`: Negative
- `-2`: Strongly Negative

### Stakeholder Types
- `Political Actor [X]`: Political figures and parties
- `Economist [X]`: Economic experts and analysts
- `Entreprenuer [X]`: Business community representatives

### Content Themes
The `Message` columns contain coded content across several thematic areas:
- Economic arguments (pro/con)
- Political dimensions
- Sovereignty concerns
- Technical readiness assessments
- Historical comparisons
- Referendum discussions

## 📈 Potential Use Cases

1. **Media analysis**: Track how different outlets frame the Euro adoption debate
2. **Sentiment tracking**: Monitor changes in public discourse over time
3. **Stakeholder mapping**: Identify key actors and their positions
4. **Narrative analysis**: Study the evolution of arguments and counter-arguments
5. **Policy research**: Inform understanding of public opinion formation

## 🛠️ Technical Details

- **Format**: Excel (.xlsx)
- **Encoding**: UTF-8
- **Structure**: Wide format with multiple message columns capturing different aspects of each media item
- **Missing Data**: Some columns may contain empty cells where information wasn't available or applicable

## 📝 Usage Notes

- The data is best analyzed using statistical software (R, Python, SPSS) or spreadsheet applications
- Multiple message columns for each record should be analyzed together for complete context
- Sentiment scores represent coder assessments rather than automated sentiment analysis
- Some engagement metrics may be zero where social media data wasn't available

## 🤝 Contributing

This dataset is provided as-is for research purposes. For questions, corrections, or collaboration inquiries, please open an issue in this repository.

## 🙏 Acknowledgments

This research is part of the GATE project funded by the Horizon 2020 WIDESPREAD-2018-2020 TEAMING Phase 2 Programme under grant agreement no. 857155, the Programme "Research, Innovation and Digitalization for Smart Transformation" 2021-2027 (PRIDST) under grant agreement no. BG16RFPR002-1.014-0010-C01 and, the project BROD (Bulgarian-Romanian Observatory of Digital Media) funded by the Digital Europe Programme of the European Union under contract number 101083730.

---

*Last Updated: [Date]*
*Contact: [Your Contact Information]*
