# Syed Imran Abidi

I'm a tech lead working on software for the solar and renewable energy industry. Most of my work is data-heavy web apps: dashboards, reporting automation and internal platforms, built with TypeScript, Node.js, GraphQL and React on Azure.

Lately I've also been writing Rust for the part of the stack that sits next to the hardware.

## What I'm working on

**[rusty-sunspec-collector](https://github.com/imrans110/rusty-sunspec-collector)** reads data from solar inverters, meters and batteries that speak SunSpec over Modbus. It works out which data models each device supports, decodes the values using the official SunSpec definitions, and sends them to Kafka. It runs on small x86 and ARM gateways, and keeps data in a local buffer when the network drops.

It's at version 0.5.0. So far it has only been tested against the simulator that comes with it, so if you have a SunSpec device and can try it, the [device report form](https://github.com/imrans110/rusty-sunspec-collector/issues/new?template=device_report.yml) helps a lot, even if the answer is "it didn't work".

## What I use

- At work: TypeScript, Node.js, GraphQL, React, Next.js, Tailwind, MongoDB, SQL, Azure (Functions, Storage, Pipelines)
- On my own projects: Rust, Modbus, Kafka, SQLite, Docker, GitHub Actions
- Now and then: Electron for desktop apps

## Contact

- LinkedIn: [linkedin.com/in/imrans110](https://www.linkedin.com/in/imrans110/)
- Email: imrans110@hotmail.com
