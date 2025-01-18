# EcoCommit
## Empowering IT Professionals for a more Sustainable Future 🌍
EcoCommit is an open-source initiative dedicated to helping software developers reduce their environmental impact through actionable strategies, (automated) tests and awareness.

## Mission

Reducing the negative climate impact of technology by making more responsible choices regarding technology.

## Rationale and Origins

This project was born in The Netherlands (Europe) in January 2025 with the rising temperatures due to climate change and the increasing energy demands of the technology industry. I experienced a lack of actionable recommendations for IT professionals, including (web) developers, engineers, architects, database administrators, and DevOps teams.

## Core Components

I intend to develop this project into roughly these four parts:

1. *Actionable tasks* in the form of text, in both machine-readable and human-readable formats identified by a unique number (for example similar to the CVE numbering system) for reference.
2. *Automatic test rules* for those *actionable tasks* that can in the future be implemented in:
    - an online (client-side) and/or;
    - an offline (cross-platform) scanning tool and/or;
    - a self-assessment questionary (for tasks that cannot easily be tested automatically)
3. *Scanning tools* that can apply these *automatic test rules* either on a URL to scan or on source-code to scan
4. *IDE integration* of the test rules with IDE such as VS Code (for example through projects like DevSkim)

I tend to make things machine-readable where possible, likely using the JSON format. I intent do develop a JSON schema for validation as well. So that other integrations in the future are made easier. The actionable tasks numbers are just incrementally assigned should contain if applicable a title, description, impact, remediation strategy, category, tags, test type and if possible references to evidence.

## Excuses and examples

- But, hardware might become more energy efficient.
- But, electricity is/might become greener.
- But, CO2 might be compensated for.

While future developments may address these issues, there are immediate actions you can take today to make a positive impact. Whatever the future outcome, today you can already make a positive impact with sometimes very simple adjustments. For example reducing the compute required will immediately (or after the next release) affect the energy usage. Using proper caching and compression on high traffic websites might drastically reduce the internet bandwidth and therefore the global energy usage.

This project tends to simply develop a repository rich of knowledge with actionable tasks that can be applied when choosing 
It should serve as a best-practice of actionable tasks that can guide developers and other IT professionals in reducing our climate footprint. *For those seeking for yet another reason to use these best-practices where possible: it will likely reduce costs too.*

## Help wanted

I intend to actively maintain this repository and develop it along with necessary tools or integrations in my spare time. But as of january 2025, this project is merely an idea, in design phase. Every idea, discussion, or interaction to help achieve this goal is greatly appreciated.
