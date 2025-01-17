---
blocks:
  - tagline: ''
    headline: Machine Transliteration
    text: >
      Indic languages are written in a variety of scripts (Brahmi family of
      abugida scripts, Arabic-derived abjad scripts, and even alphabetic Roman
      script). This diversity makes it challenging to support mechanisms which
      are convenient for typing or creating content in these diverse languages
      and scripts. Most Indian users are comfortable with the Roman keyboard and
      thus an optimal solution that users find beneficial is automatic
      transliteration of the romanized input into the native script. To enable
      this, at AI4Bharat, we have undertaken the task of creating large-scale
      transliteration corpora for Indic languages along with models for
      transliteration of romanized inputs into native scripts.
    _template: hero
  - quote: Our Contributions
    author: Phil Karlton
    color: default
    _template: testimonial
  - items:
      - icon:
          color: ''
          style: float
          name: ''
        title: "\U0001F4DCAksharantar dataset"
        link: /aksharantar
        comingSoon: false
        updated: false
        text: >-
          The largest publicly available

          parallel transliteration corpora containing 26M

          word pairs spanning 21 languages mined from Wikidata, Samanantar and
          IndicCorp. It also contains a challenging and diverse benchmark for
          evaluating transliteration models.
      - icon:
          color: ''
          style: float
          name: ''
        title: "\U0001F680IndicXlit model"
        link: /indic-xlit
        comingSoon: false
        updated: false
        text: >-
          A multilingual transformer based model for transliteration from
          romanized input to native language scripts supporting 21 languages.
          This model is trained using Aksharantar corpus and at the time of its
          release was the state of the art open source model as evaluated on
          Google's Dakshina benchmark and our Aksharantar benchmark.
      - icon:
          color: ''
          style: float
          name: ''
        title: IndicLangID
        link: ''
        comingSoon: true
        updated: false
        text: >-
          A model for identifying the language of romanized content on social
          media. This model will be trained using the large number of romanized
          Indian language words in Aksharantar.
      - icon:
          color: ''
          style: float
          name: chat
        title: ⌨️IndicXlit Keyboard
        link: 'https://xlit.ai4bharat.org/'
        linkPlaceholder: Try online →
        comingSoon: false
        updated: false
        text: >-
          A transliteration interface (En-Indic online keyboard) that converts
          romanized text into Indic text as you type.
      - icon:
          color: ''
          style: float
          name: chat
        title: "\U0001F4BBIndicXlit Converter"
        link: 'https://xlit.ai4bharat.org/converter'
        linkPlaceholder: Try online →
        comingSoon: false
        updated: false
        text: >-
          A transliteration interface that converts Indic text into romanized
          text and vice versa.
      - icon:
          color: ''
          style: float
          name: ''
        title: "\U0001F4F1IndicSwipe"
        link: 'https://swipe.ai4bharat.org/'
        comingSoon: false
        updated: false
        text: >-
          An on-going research for creating swipe-based keypad typing on Android
          devices for Indic languages
    _template: featuresAlt
  - quote: Our Partners
    author: Phil Karlton
    color: default
    _template: testimonial
  - items:
      - icon:
          color: ''
          style: float
          name: ''
        title: Pratham Books
        text: >-
          We have partnered with Pratham Books to enable romanized keyboards in
          their translation interface for low resource languages such as Bodo,
          Kashmiri, Konkani, Maithili, Nepali and Urdu.
    _template: flatCardsGrid
  - tagline: ''
    headline: IndicXlit Workshop
    text: >
      On 28th July, we are conducting a workshop to demonstrate our datasets,
      models, and applications.
    actions:
      - label: Sign Up to Attend
        type: button
        icon: true
        link: 'https://forms.office.com/r/vddNi9fuqS'
      - label: Learn More
        type: link
        icon: false
        link: /
    _template: hero
---

