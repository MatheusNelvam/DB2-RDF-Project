# DB2-RDF-Project MONC GROUP

## General Project Description: Supply Chain Ontology

This project involves the creation of an ontology to model concepts and relationships within a supply chain. The ontology is a formal, semantic representation of the supply chain domain using the OWL (Web Ontology Language) to structure and define entities relevant to supply chain management.

## Project Objective

The primary goal is to provide a clear and semantic framework to represent different elements involved in a supply chain, such as supply chain projects, shipments, vendors, products, countries, etc. This ontology enhances understanding and interoperability among systems dealing with supply chain-related information.

## How to Use

To utilize the ontology, follow these steps:

1. Clone the repository.
2. Open the ontology in Protegé, an ontology editing tool.
3. Add instances, define relationships, and save your changes.

### Installing the software

1. Download Protégé Desktop for your OS from the [Protégé website](https://protege.stanford.edu/).
2. Extract the compressed file to a location of your choice.
3. Run the executable or shell script.
4. If prompted, install the Snap SPARQL Query Plugin.

### Opening Ontology Files

- Open an ontology file in your system (e.g., .ttl, .owl) by clicking `File -> Open`.
- Open an ontology file on the web by copying its URL, then click `File -> Open by URL` and paste the URL into the URI text box.



Ensure you've installed the Snap SPARQL Query Plugin.

### Key Components

The main classes in the ontology include:

- **Project:** Represents specific projects related to the supply chain.
- **Shipment:** Represents the physical shipment of products.
- **Vendor:** Represents suppliers or sellers.
- **Product:** Represents specific products.
- **Country:** Represents countries.
- **PQSupplyChain:** Represents PQ-related data.

Properties such as `hasShipment`, `hasProduct`, `hasVendor`, `hasCountry`, `hasPQSupplyChain` are used to define specific relationships and attributes.

### Queries Execution
#### Configuring Protégé to Run SPARQL Queries
To execute SPARQL queries:

1. Open Protégé with an ontology.
2. Go to `Window -> Tabs -> SPARQL Query` and enable it.
3. Click the `SPARQL Query` tab.
4. Remove the view by clicking the tiny rightmost box marked with an X.
5. Enable `Window -> Views -> Query views -> Snap SPARQL Query`.
6. Click the empty view.
7. Start your reasoner (ensure HermiT is selected).
8. Type your query and click `Execute`.

### Disclaimer

This project is a conceptual representation and not intended for ready-to-use implementation. Adaptations may be required based on user needs.

We hope this ontology serves as a valuable tool for modeling and understanding supply chain processes, promoting interoperability, and facilitating communication among systems dealing with supply chain information.
