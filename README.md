# nokternel-style-guide
A practical approach to styling Unreal Engine code.

# Code
Fortunately, the Unreal Header Tool (UHT), which runs early in the Engine's build process, enforces several of these rules by default. These rules provide an additional level of uniformity on top for those things that are not covered by UHT.

## 1. General
### 1.1 Casing
All type definitions, variables, and functions should be in PascalCase (capitalize every word). Local variables and parameters should be in dromedaryCase (capitalize every word except the first).

## 2. Type Definitions
The following rules apply only to Blueprint-exposable types.

### 2.1 Classes
#### 2.1.1 Actor - Prefix: `A`
#### 2.1.2 UObject - Prefix: `U`
### 2.2 UStructs - Prefix: `F`
### 2.3 UEnums - Prefix: `E`

## 3. Variables
### 3.1 Member variables

### Delegates
`a`
