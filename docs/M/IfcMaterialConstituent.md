IfcMaterialConstituent
======================
_IfcMaterialConstituent_ is a single and identifiable part of an element which
is constructed of a number of part (one or more) each having an individual
material. The association of the material constituent to the part is provided
by a keyword as value of the _Name_ attribute. In order to identify and
distinguish the part of the shape representation to which the material
constituent applies the _IfcProductDefinitionShape_ of the element has to
include instances of _IfcShapeAspect_, using the same keyword for their _Name_
attribute.  
  
> NOTE  See the "Material Use Definition" at the individual element to which
> an _IfcMaterialConstituentSet_ may apply for a required or recommended
> definition of such keywords as value for _IfcMaterialConstituent.Name_.  
  
> HISTORY\S\ New entity in IFC4  
[ _bSI
Documentation_](https://standards.buildingsmart.org/IFC/DEV/IFC4_2/FINAL/HTML/schema/ifcmaterialresource/lexical/ifcmaterialconstituent.htm)


Attribute definitions
---------------------
| Attribute                | Description                                                                                                                                                                   |
|--------------------------|-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| Material                 |                                                                                                                                                                               |
| ToMaterialConstituentSet |                                                                                                                                                                               |
| Name                     | The name by which the material constituent is known.                                                                                                                          |
| Description              | Definition of the material constituent in descriptive terms.                                                                                                                  |
| Fraction                 | Optional provision of a fraction of the total amount (volume or weight) that applies to the _IfcMaterialConstituentSet_ that is contributed by this _IfcMaterialConstituent_. |
| Category                 | Category of the material constituent, e.g. the role it has in the constituent set it belongs to.                                                                              |

