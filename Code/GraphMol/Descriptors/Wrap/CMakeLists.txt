rdkit_python_extension(rdMolDescriptors rdMolDescriptors.cpp
                       DEST Chem
                       LINK_LIBRARIES
LINK_LIBRARIES Descriptors PartialCharges Fingerprints FileParsers SmilesParse Subgraphs
SubstructMatch MolTransforms GraphMol EigenSolvers DataStructs RDGeneral RDGeometryLib RDBoost )

