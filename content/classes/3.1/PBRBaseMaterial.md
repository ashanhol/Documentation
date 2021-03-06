---
TAGS:
---
## Description

class [PBRBaseMaterial](/classes/3.1/PBRBaseMaterial) extends [PushMaterial](/classes/3.1/PushMaterial)



## Constructor

## new [PBRBaseMaterial](/classes/3.1/PBRBaseMaterial)(name, scene)

Instantiates a new [PBRMaterial](/classes/3.1/PBRMaterial) instance.

         * @param name The material name

#### Parameters
 | Name | Type | Description
---|---|---|---
 | name | string |  The material name
 | scene | [Scene](/classes/3.1/Scene) |  The scene the material will be use in.
## Members

### useLogarithmicDepth : boolean



## Methods

### getClassName() &rarr; string


### needAlphaBlending() &rarr; boolean


### needAlphaTesting() &rarr; boolean


### getAlphaTestTexture() &rarr; [BaseTexture](/classes/3.1/BaseTexture)


### isReadyForSubMesh(mesh, subMesh, useInstances) &rarr; boolean



#### Parameters
 | Name | Type | Description
---|---|---|---
 | mesh | [AbstractMesh](/classes/3.1/AbstractMesh) | 
 | subMesh | [SubMesh](/classes/3.1/SubMesh) | 
optional | useInstances | boolean | 
### buildUniformLayout() &rarr; void


### unbind() &rarr; void


### bindOnlyWorldMatrix(world) &rarr; void



#### Parameters
 | Name | Type | Description
---|---|---|---
 | world | [Matrix](/classes/3.1/Matrix) | 

### bindForSubMesh(world, mesh, subMesh) &rarr; void



#### Parameters
 | Name | Type | Description
---|---|---|---
 | world | [Matrix](/classes/3.1/Matrix) | 
 | mesh | [Mesh](/classes/3.1/Mesh) | 
 | subMesh | [SubMesh](/classes/3.1/SubMesh) | 
### getAnimatables() &rarr; IAnimatable[]


### dispose(forceDisposeEffect, forceDisposeTextures) &rarr; void



#### Parameters
 | Name | Type | Description
---|---|---|---
optional | forceDisposeEffect | boolean | 
optional | forceDisposeTextures | boolean | 
