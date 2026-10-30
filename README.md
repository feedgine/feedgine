### Hi there

I work with messy real-world data. The sort that arrives as scans, scraped pages, thirty-year-old exports in three incompatible encodings, and occasionally with someone’s brilliant idea of how to make everything easier.

I like turning all that into something structured, reliable and actually useful. These days I also spend quite a lot of time on analysis and visualisation. After all the work of getting the data into shape, it’s nice to finally see what it says.

I like reproducible pipelines, implementing algorithms from research papers, and figuring out how to make AI assistants reliable enough to trust with real work.

“It usually works” is not, regrettably, a specification.

I also have a weakness for making complicated things look simple. Ideally simple enough that nobody needs to know how much work went into them.

### Now

After spending so much time collecting and organising data, I’m increasingly interested in what happens once it's cleaned, structured and finally behaving itself.

I want to explore how to tell stories through data visualisation. Not just make pretty charts, but find the patterns, unexpected connections and little stories hiding inside complicated datasets.

I like starting with a question, following the data, and occasionally discovering that the interesting answer belongs to a completely different question.

The challenge is to make all that complexity understandable without throwing away the interesting bits.

And if the result happens to be beautiful, even better.

### Projects

**PedigreeInsights / PedigreeInsightsWeb** — an application for exploring dog pedigrees at scale. Over 100,000 animals, with instant search and printable certificates.

It calculates inbreeding and relatedness using the Meuwissen & Luo and Colleau algorithms, rather than simply trusting the figures stored by legacy breeding software.

This began as a sensible precaution and ended with the discovery that some of those figures were spectacularly wrong.

There is nothing quite like implementing an algorithm from a scientific paper and discovering that the old software has been confidently making things up for years.

The project also allowed me to build and publish a consolidated global studbook for a single breed: **pedigree.japanesespitz.org**.

Around 63,000 dogs reconciled from registries, databases and printed studbooks that previously existed only as scans.

Much of the work comes down to one simple question:

*Which dog is this?*

Five sources then provide six answers.

**SEPA credit transfer → Wise** — a utility for converting SEPA pain.001.001.03 files containing salaries, taxes, contributions and supplier invoices into Wise batch-payment CSVs, while preserving the mandatory Slovenian payment reference (*sklic*).

A small utility born from the traditional software-development methodology of: surely I cannot be the only person annoyed by this.

**AI package architecture** — a way of building LLM assistants as modular packages: base, skills, SOPs and coordinator.

The idea is to make them auditable, maintainable and possible to hand over to another person without also handing over three months of chat history and wishing them luck.

**SEO capacity modelling** — a framework for estimating the realistic ceiling of organic search before anyone commits a budget to it.

One of its supported outputs is “not worth it”, a feature strangely absent from many marketing tools.

**Older projects** include OCR parsers for historic studbooks and fixing a decade-old day/month date swap that had quietly corrupted several thousand birthdates.

The bug had survived for years.

The dogs, fortunately, had not noticed.
