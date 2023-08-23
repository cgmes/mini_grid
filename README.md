# Mini Grid

The Mini Grid Test Configuration for the ENTSO-E Common Grid Model Exchange Standard (CGMES) Conformity Assessment.

Mini Grid test configuration models are planned to be used only for short-circuit calculations (according to
the IEC 60909-4 standard), but not for load flow and dynamic calculations.

## Trig

The "trig" branch of this repository contains the Mini Grid Test Configuration in [TriG](https://www.w3.org/TR/trig/) format.
CIM/XML is a domain specific syntax used in the energy sector.
It is based on RDF/XML, but is not compatible.
As a result, it can not be used directly with generic RDF tools and libraries.
TriG is an extension to [TURTLE](https://www.w3.org/TR/turtle/) for representing complete RDF datasets.
TURTLE and TriG are well established syntaxes for RDF and are supported by many tools and libraries.
TriG allows metadata to be associated with named graphs.
This allows separate parts of a CGMES model to be stored in a single text file and avoids the need to use an opaque ZIP archive.

## Note

This is an unofficial source for the Mini Grid Test Configuration.
Please refer to [ENTSO-E](https://www.entsoe.eu) for official resources.