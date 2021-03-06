IfcMaterialRelationship
=======================
_IfcMaterialRelationship_ defines a relationship between part and whole in
material definitions (as in composite materials). The parts, expressed by the
set of _RelatedMaterials_, are material constituents of which a single
material aggregate is composed.  
  
> HISTORY\S\ New entity in IFC4  
[ _bSI
Documentation_](https://standards.buildingsmart.org/IFC/DEV/IFC4_2/FINAL/HTML/schema/ifcmaterialresource/lexical/ifcmaterialrelationship.htm)


Attribute definitions
---------------------
| Attribute        | Description                                                                                                                                                                                                                                                                                                                                   |
|------------------|-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| RelatedMaterials |                                                                                                                                                                                                                                                                                                                                               |
| RelatingMaterial |                                                                                                                                                                                                                                                                                                                                               |
| Expression       | Information about the material relationship refering for example to the amount of related materials in the composite material. \X\0D> NOTE  Any formal meaning of the _Expression_ string value has to be established in model view definitions or implementer agreements. No such formal language is provided as part of this specification. |

