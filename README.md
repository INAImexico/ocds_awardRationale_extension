# Award rationale
## Description:

The award rationale is a short text describing the reasons why the award was made for a particular supplier. It is a data that can be useful to understand, in a simple way, the end of the evaluation period. In Mexico, from INAI we have this data in our system and its publication is mandatory according to our Freedom for Information Act.

## Proposal:

Add a new field named “rationale” to the “Award” object.

### Schema

  - Awards
    - Award
      - id
      - tittle
      - description
      - rationale (string, null)
      - [...]

## Defining texts:


**Code** | **Title** | **Description**
--|--|--
rationale | Award rationale | A short summary of the reasons for making this specific award, and/or selecting the particular supplier, provided in free text. More detail can be provided in attached documents.

## Issues 

Report issues for this extension in the [standard repository](https://github.com/open-contracting/standard/issues/625) of the Open Contracting Partnership.
