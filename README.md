### Hi there

I build structures for messy real-world data the sort that arrives as scans, scraped pages, thirty-year-old exports in three incompatible encodings, and occasionally with the people idea how to make things easy.

I like reproducible data pipelines, algorithms taken straight from papers, and making artificial assistants reliable enough to hand real work to. “It usually works” is not, regrettably, a specification.

### Currently working

PedigreeInsights — a  app for exploring dog pedigrees at scale. 100k+ animals with instant search and printable certificates.

It computes inbreeding and relatedness itself using Meuwissen & Luo and Colleau, rather than trusting the figures stored by legacy breeding software.

This began as a sensible precaution and ended with the discovery that some of those figures were spectacularly wrong. There is nothing quite like implementing an algorithm from a scientific paper and discovering that the old software has been confidently making things up for years.

I’m also building a consolidated global studbook for a single breed: around 62,000 dogs reconciled from registries, databases and printed studbooks that previously existed only as scans.

Much of the work consists of asking a simple question:

Which dog is this?

Five sources then provide six answers.

### Past projects

- SEPA credit transfer → Wise — converting SEPA pain.001.001.03 files containing salaries, taxes, contributions and supplier invoices into Wise batch-payment CSVs while preserving the mandatory Slovenian payment reference (sklic). A small utility born from the traditional software-development methodology of: surely I cannot be the only person annoyed by this.

- AI package architecture — a way of building LLM assistants as modular packages — base, skills, SOPs and coordinator — so they can be audited, maintained and handed to another person without also handing over three months of chat history and wishing them luck.

- SEO capacity modelling — a framework for estimating the realistic ceiling of organic search before anyone commits budget to it. One of its supported outputs is “not worth it”, a feature strangely absent from many marketing tools.

- Older projects include OCR parsers for historic studbooks and fixing a decade-old day/month date swap that had quietly corrupted several thousand birthdates.

The bug had survived for years.

The dogs, fortunately, had not noticed. 
