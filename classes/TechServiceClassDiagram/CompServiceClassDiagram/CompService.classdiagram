<?xml version="1.0" encoding="utf-8"?>
<logicalClassDesignerModel xmlns:dm0="http://schemas.microsoft.com/VisualStudio/2008/DslTools/Core" xmlns:dm1="http://schemas.microsoft.com/dsltools/Kernel" xmlns:dm2="http://schemas.microsoft.com/dsltools/Component" xmlns:dm3="http://schemas.microsoft.com/dsltools/Activity" xmlns:dm4="http://schemas.microsoft.com/dsltools/UseCase" xmlns:dm5="http://schemas.microsoft.com/dsltools/Interaction" xmlns:dm6="http://schemas.microsoft.com/dsltools/UmlModelLibrary" xmlns:dm7="http://schemas.microsoft.com/dsltools/UmlDiagrams" xmlns:dm8="http://schemas.microsoft.com/dsltools/ModelStore" dslVersion="1.0.0.0" Id="586f19b3-0f68-4543-88c8-7759ebdb2a43" name="CompService" linkedPackageId="daa639ff-2fb2-4b9a-b23a-20b1161631fe" xmlns="http://schemas.microsoft.com/dsltools/LogicalClassDesigner">
  <packagedElements>
    <logicalClassDesignerModelHasTypes>
      <class Id="eb5a3e5e-d4a7-4a33-abd3-e0b1cb37c416" name="Person {abstract}" isAbstract="true" isLeaf="false" isActiveClass="false">
        <elementDefinition Id="2b1ee075-65ea-41e2-8b82-541bbee983e0" />
        <ownedAttributesInternal>
          <property Id="3707557a-48fd-4b8d-8f70-0ffe4421c477" name="Name" isLeaf="false" isStatic="false" isReadOnly="false" isUnique="false" isDerived="false" isDerivedUnion="false" aggregation="None" isComposite="false">
            <elementDefinition Id="4d10921f-950d-44fb-9e5c-57c3d7fd3095" />
            <type_NamedElement>
              <referencedTypeMoniker Id="faf4849f-8756-4979-b0da-605e57790912" LastKnownName="String" />
            </type_NamedElement>
          </property>
          <property Id="8933d4e5-1d17-4909-a7d9-8141786049bd" name="PhoneNum" isLeaf="false" isStatic="false" isReadOnly="false" isUnique="false" isDerived="false" isDerivedUnion="false" aggregation="None" isComposite="false">
            <elementDefinition Id="29b3dd87-ea90-4736-83ac-cf3155ebfc91" />
            <type_NamedElement>
              <referencedTypeMoniker Id="0d48b67c-a7ab-4676-898b-2138da127268" LastKnownName="String" />
            </type_NamedElement>
          </property>
          <property Id="29acfe18-583d-4547-be93-bb2d0908127a" name="id" isLeaf="false" isStatic="false" isReadOnly="false" isUnique="false" isDerived="false" isDerivedUnion="false" aggregation="None" isComposite="false">
            <elementDefinition Id="1318cb5f-3e52-4e0f-892c-5748f0a91068" />
            <type_NamedElement>
              <referencedTypeMoniker Id="bed62a32-5b87-4e40-9259-b99a5a7769a5" LastKnownName="Integer" />
            </type_NamedElement>
          </property>
          <property Id="f93e941a-a668-4363-86c2-9342dd6131e1" name="DelTime" isLeaf="false" isStatic="false" isReadOnly="false" isUnique="false" isDerived="false" isDerivedUnion="false" aggregation="None" isComposite="false">
            <elementDefinition Id="372b8ad3-73e9-44b3-8381-20d34b53cb5f" />
            <type_NamedElement>
              <referencedTypeMoniker Id="5e95a766-896f-41c7-8951-778ddf708d7a" LastKnownName="DateTime" />
            </type_NamedElement>
          </property>
        </ownedAttributesInternal>
      </class>
    </logicalClassDesignerModelHasTypes>
    <packageHasNamedElement>
      <referencedType Id="faf4849f-8756-4979-b0da-605e57790912" name="String" isAbstract="false" isLeaf="false" cachedFullName="String">
        <elementDefinition Id="59259974-6d55-42c6-b7bd-763d77ac8ef9" />
      </referencedType>
    </packageHasNamedElement>
    <packageHasNamedElement>
      <referencedType Id="0d48b67c-a7ab-4676-898b-2138da127268" name="String" isAbstract="false" isLeaf="false" cachedFullName="String">
        <elementDefinition Id="59259974-6d55-42c6-b7bd-763d77ac8ef9" />
      </referencedType>
    </packageHasNamedElement>
    <packageHasNamedElement>
      <referencedType Id="bed62a32-5b87-4e40-9259-b99a5a7769a5" name="Integer" isAbstract="false" isLeaf="false" cachedFullName="Integer">
        <elementDefinition Id="220a3521-e091-4221-bae9-3ef9018e845c" />
      </referencedType>
    </packageHasNamedElement>
    <logicalClassDesignerModelHasTypes>
      <class Id="a5c00f8f-2e99-4e50-af3d-5016ef70a856" name="Client" isAbstract="false" isLeaf="false" isActiveClass="false">
        <elementDefinition Id="3cbddadd-d029-40c3-b045-8bccb04a6bc8" />
        <generalsInternal>
          <generalization Id="66c4fca7-1890-4939-b748-69ea4e30bd68" isSubstitutable="false">
            <classMoniker Id="eb5a3e5e-d4a7-4a33-abd3-e0b1cb37c416" LastKnownName="Person {abstract}" />
            <elementDefinition Id="79482a8e-bfe0-488e-99e7-7e5161482e3b" />
          </generalization>
        </generalsInternal>
        <ownedOperationsInternal>
          <operation Id="d7e983af-c12a-4cb3-9d4d-561c9ca25577" name="Client" isLeaf="false" isStatic="false" isAbstract="false" concurrency="Sequential" isQuery="false">
            <elementDefinition Id="15b52d71-d74d-42e8-894a-abc21ef39e20" />
            <ownedParameters>
              <operationHasOwnedParameters>
                <parameter Id="eb465a28-ae95-4aee-9f1f-957880af775c" direction="Return" isUnique="false">
                  <elementDefinition Id="1f1fad0d-49b6-4a07-89bd-f093ba491b84" />
                  <type_NamedElement>
                    <referencedTypeMoniker Id="62e1c591-1fc8-4d49-889d-ba3d80faa959" LastKnownName="void" />
                  </type_NamedElement>
                </parameter>
              </operationHasOwnedParameters>
            </ownedParameters>
          </operation>
          <operation Id="455ec6aa-20cc-409d-8242-fb299dcf6b1f" name="AddClient" isLeaf="false" isStatic="false" isAbstract="false" concurrency="Sequential" isQuery="false">
            <elementDefinition Id="1ae1308a-e05b-430f-ab27-e7b77207f01e" />
            <ownedParameters>
              <operationHasOwnedParameters>
                <parameter Id="9c2b590e-bd85-4585-8bde-40f780a92ae5" direction="Return" isUnique="false">
                  <elementDefinition Id="a034622f-4910-4d1d-9239-b1f0b2704a94" />
                  <type_NamedElement>
                    <referencedTypeMoniker Id="6a45fed8-1689-4fa9-8e39-f876365db554" LastKnownName="bool" />
                  </type_NamedElement>
                </parameter>
              </operationHasOwnedParameters>
            </ownedParameters>
          </operation>
          <operation Id="714d4235-dab9-439f-a01c-3cdd4898727e" name="DelClient" isLeaf="false" isStatic="false" isAbstract="false" concurrency="Sequential" isQuery="false">
            <elementDefinition Id="05b89494-fce1-42b8-9eab-361632ddfcc9" />
            <ownedParameters>
              <operationHasOwnedParameters>
                <parameter Id="46c072ad-69a1-4334-8e34-650e4b577993" direction="Return" isUnique="false">
                  <elementDefinition Id="3a7a9821-6da8-4308-a55b-08b3e682bbe7" />
                  <type_NamedElement>
                    <referencedTypeMoniker Id="6a45fed8-1689-4fa9-8e39-f876365db554" LastKnownName="bool" />
                  </type_NamedElement>
                </parameter>
              </operationHasOwnedParameters>
            </ownedParameters>
          </operation>
          <operation Id="3dbff8e1-bae2-4e83-b3e9-ce96147e6bbe" name="EditClient" isLeaf="false" isStatic="false" isAbstract="false" concurrency="Sequential" isQuery="false">
            <elementDefinition Id="292bab0a-fda7-4db3-a3d8-ba1dcea716b6" />
            <ownedParameters>
              <operationHasOwnedParameters>
                <parameter Id="3231adf0-e1b5-49bd-a419-630351d83f70" direction="Return" isUnique="false">
                  <elementDefinition Id="e4a251c2-20c8-4f14-a152-cb9ad22777f2" />
                  <type_NamedElement>
                    <referencedTypeMoniker Id="6a45fed8-1689-4fa9-8e39-f876365db554" LastKnownName="bool" />
                  </type_NamedElement>
                </parameter>
              </operationHasOwnedParameters>
            </ownedParameters>
          </operation>
          <operation Id="39aeeace-1df5-4714-9db3-4c26dd619ca2" name="CalcSale" isLeaf="false" isStatic="false" isAbstract="false" concurrency="Sequential" isQuery="false">
            <elementDefinition Id="2b304bdb-666f-45e6-a8d7-902dc85f0b83" />
            <ownedParameters>
              <operationHasOwnedParameters>
                <parameter Id="5df61e25-3235-4774-8568-9014313fd77e" direction="Return" isUnique="false">
                  <elementDefinition Id="2de23a1b-acef-4909-9c0d-d7b77e3aca21" />
                  <type_NamedElement>
                    <referencedTypeMoniker Id="d0e2218a-5be7-46cf-97a2-091e3a6a80e0" LastKnownName="decimal" />
                  </type_NamedElement>
                </parameter>
              </operationHasOwnedParameters>
            </ownedParameters>
          </operation>
          <operation Id="360d3703-aec1-427f-997d-9bf97e2a9278" name="CountClientOrders" isLeaf="false" isStatic="false" isAbstract="false" concurrency="Sequential" isQuery="false">
            <elementDefinition Id="e7035d8b-20a9-4564-809b-d0fd0024056f" />
            <ownedParameters>
              <operationHasOwnedParameters>
                <parameter Id="ba37a994-06ac-45b4-ac9f-5c0e6e256ac8" direction="Return" isUnique="false">
                  <elementDefinition Id="6f823d14-1e9b-42d3-99e1-c8c778638507" />
                  <type_NamedElement>
                    <referencedTypeMoniker Id="de578a74-cb65-4d29-833c-4c0b903c29db" LastKnownName="int" />
                  </type_NamedElement>
                </parameter>
              </operationHasOwnedParameters>
            </ownedParameters>
          </operation>
        </ownedOperationsInternal>
      </class>
    </logicalClassDesignerModelHasTypes>
    <logicalClassDesignerModelHasTypes>
      <class Id="f87435e5-83d1-45e9-8965-813f6d8a5e7d" name="Master" isAbstract="false" isLeaf="false" isActiveClass="false">
        <elementDefinition Id="939286e1-c9aa-47d9-ad7b-458d2a0f2614" />
        <generalsInternal>
          <generalization Id="49fcd143-0655-406f-92d7-c39b1f7a90e2" isSubstitutable="false">
            <classMoniker Id="9e4efbc8-78da-4018-bab1-5d0f33397b70" LastKnownName="Employee {abstract}" />
            <elementDefinition Id="688fec01-97a7-45cc-b615-49d21644adcd" />
          </generalization>
        </generalsInternal>
        <targetEnds>
          <association Id="07825914-5487-4476-bd19-f8972295212b" isDerived="false" sourceEndRoleName="Master" targetEndRoleName="Categorie" isLeaf="false" isAbstract="false">
            <classMoniker Id="ecb68bbe-7ceb-4436-a662-49d34c98b121" LastKnownName="Category" />
            <relationshipOwnedElementsInternal>
              <associationHasOwnedEnds>
                <memberEnd Id="19776572-2b61-44e7-8bef-484e0c6596fc" name="Master" isLeaf="false" isStatic="false" isReadOnly="false" isDerived="false" isDerivedUnion="false" aggregation="Composite" isComposite="false" isNavigableOwned="false">
                  <lowerValueInternal>
                    <literalString Id="82ccb93b-4555-4ca8-b493-1204cab83d7d" name="Lower" value="1">
                      <elementDefinition Id="8430249b-607b-4a19-9c39-0d791308cbec" />
                    </literalString>
                  </lowerValueInternal>
                  <upperValueInternal>
                    <literalString Id="0c5a19b3-f3c9-4357-92b8-37c7fcedde1f" name="Upper" value="*">
                      <elementDefinition Id="27f3a4c8-f31d-4f2b-951e-4a0b656d1229" />
                    </literalString>
                  </upperValueInternal>
                  <elementDefinition Id="2981c747-8cf2-498c-8911-f5fcb2da7454" />
                </memberEnd>
              </associationHasOwnedEnds>
              <associationHasOwnedEnds>
                <memberEnd Id="0ce2b534-48c5-405c-ae4d-bd5bccba96ce" name="Categorie" isLeaf="false" isStatic="false" isReadOnly="false" isDerived="false" isDerivedUnion="false" aggregation="None" isComposite="true">
                  <lowerValueInternal>
                    <literalString Id="66d3b006-39af-4d45-944d-d839d03160b2" name="Lower" value="1">
                      <elementDefinition Id="eaf952ce-43a1-4e18-9488-60f42397e61e" />
                    </literalString>
                  </lowerValueInternal>
                  <upperValueInternal>
                    <literalString Id="7c283c96-f6a8-42b8-a873-5974ff071277" name="Upper" value="*">
                      <elementDefinition Id="7abeeb3f-b66d-4f6f-bf0a-c0a6f625f8de" />
                    </literalString>
                  </upperValueInternal>
                  <elementDefinition Id="bda01406-4bba-4094-82c6-98c35751c2b3" />
                </memberEnd>
              </associationHasOwnedEnds>
            </relationshipOwnedElementsInternal>
            <elementDefinition Id="961295b5-466e-42ce-beb4-f05512810bf4" />
          </association>
        </targetEnds>
        <ownedOperationsInternal>
          <operation Id="6257d3c9-9dc6-4d20-9dc4-7daf133a7dfc" name="Master" isLeaf="false" isStatic="false" isAbstract="false" concurrency="Sequential" isQuery="false">
            <elementDefinition Id="c845a016-436b-4818-aff3-750ec73c5100" />
            <ownedParameters>
              <operationHasOwnedParameters>
                <parameter Id="9db2732a-02ff-4774-a3fc-bd007702331e" direction="Return" isUnique="false">
                  <elementDefinition Id="3035dd76-4897-4bb9-92c9-d93fed129bd7" />
                  <type_NamedElement>
                    <referencedTypeMoniker Id="62e1c591-1fc8-4d49-889d-ba3d80faa959" LastKnownName="void" />
                  </type_NamedElement>
                </parameter>
              </operationHasOwnedParameters>
            </ownedParameters>
          </operation>
          <operation Id="386d5acc-5776-4796-8935-33cd8877ba38" name="AddMasterCategory" isLeaf="false" isStatic="false" isAbstract="false" concurrency="Sequential" isQuery="false">
            <elementDefinition Id="e84f213c-317b-46ce-9c7e-521091803042" />
            <ownedParameters>
              <operationHasOwnedParameters>
                <parameter Id="56f751ce-dbad-4e01-9220-bd61ba0c59e9" direction="Return" isUnique="false">
                  <elementDefinition Id="a5886613-b04c-4c1c-93e7-fb8935e70f5a" />
                  <type_NamedElement>
                    <referencedTypeMoniker Id="6a45fed8-1689-4fa9-8e39-f876365db554" LastKnownName="bool" />
                  </type_NamedElement>
                </parameter>
              </operationHasOwnedParameters>
              <operationHasOwnedParameters>
                <parameter Id="c3b60961-c974-413d-8dac-4093b25a1287" name="category" direction="In" isUnique="false">
                  <elementDefinition Id="6f3b9922-5bbf-49a3-9841-293c4823d423" />
                  <type_NamedElement>
                    <referencedTypeMoniker Id="6c593322-0955-41a8-b52b-79af32acfbe4" LastKnownName="Category" />
                  </type_NamedElement>
                </parameter>
              </operationHasOwnedParameters>
            </ownedParameters>
          </operation>
          <operation Id="ca129a00-f80e-48c6-a453-f1673db41667" name="GetMasterCategories" isLeaf="false" isStatic="false" isAbstract="false" concurrency="Sequential" isQuery="false">
            <elementDefinition Id="db209b85-6d4c-4f97-83a6-55f13676e308" />
            <ownedParameters>
              <operationHasOwnedParameters>
                <parameter Id="3986649d-ff25-425e-ab90-d4d69d72f376" direction="Return" isUnique="false">
                  <elementDefinition Id="01f5f246-accd-40e4-b0bb-050e65dd511b" />
                  <type_NamedElement>
                    <referencedTypeMoniker Id="d196a296-ba5f-447c-b890-b886fcfbc7a4" LastKnownName="List&lt;Category&gt;" />
                  </type_NamedElement>
                </parameter>
              </operationHasOwnedParameters>
            </ownedParameters>
          </operation>
          <operation Id="5efc823b-5ca9-45b1-828b-e16e9f876480" name="DelMasterCategory" isLeaf="false" isStatic="false" isAbstract="false" concurrency="Sequential" isQuery="false">
            <elementDefinition Id="09e8a2c0-24be-4a30-a324-8058bd148b36" />
            <ownedParameters>
              <operationHasOwnedParameters>
                <parameter Id="f718c7c0-c27d-4470-bfde-7adf92807733" direction="Return" isUnique="false">
                  <elementDefinition Id="e51ed4b4-f1e0-4918-8218-df4c36ffea42" />
                  <type_NamedElement>
                    <referencedTypeMoniker Id="6a45fed8-1689-4fa9-8e39-f876365db554" LastKnownName="bool" />
                  </type_NamedElement>
                </parameter>
              </operationHasOwnedParameters>
              <operationHasOwnedParameters>
                <parameter Id="5e39851b-c2b6-45f6-b5e9-a3ce47c04bde" name="category" direction="In" isUnique="false">
                  <elementDefinition Id="dc1618fc-a580-4ca0-96c0-071d756a1ca1" />
                  <type_NamedElement>
                    <referencedTypeMoniker Id="6c593322-0955-41a8-b52b-79af32acfbe4" LastKnownName="Category" />
                  </type_NamedElement>
                </parameter>
              </operationHasOwnedParameters>
            </ownedParameters>
          </operation>
          <operation Id="bcb7240a-31d2-4058-afd3-aabd5102cef9" name="AddEmployee" isLeaf="false" isStatic="false" isAbstract="false" concurrency="Sequential" isQuery="false">
            <elementDefinition Id="1c941171-0dc0-420b-8339-d8555d1e2f58" />
            <ownedParameters>
              <operationHasOwnedParameters>
                <parameter Id="43e285ab-4daa-430e-8abb-c4e1d6ba8bcf" direction="Return" isUnique="false">
                  <elementDefinition Id="0f646c15-b140-4406-9d46-e964fb07ae6d" />
                  <type_NamedElement>
                    <referencedTypeMoniker Id="6a45fed8-1689-4fa9-8e39-f876365db554" LastKnownName="bool" />
                  </type_NamedElement>
                </parameter>
              </operationHasOwnedParameters>
            </ownedParameters>
          </operation>
          <operation Id="85210de6-b78c-4f07-87b0-e9d3d183acca" name="EditEmployee" isLeaf="false" isStatic="false" isAbstract="false" concurrency="Sequential" isQuery="false">
            <elementDefinition Id="4b6ecb55-1c3c-4954-be9b-42ca06cad2fe" />
            <ownedParameters>
              <operationHasOwnedParameters>
                <parameter Id="9ad91cd9-ed88-4dc8-af61-75db203ee8d0" direction="Return" isUnique="false">
                  <elementDefinition Id="20050c9a-1267-4efe-8feb-ecd9a1514157" />
                  <type_NamedElement>
                    <referencedTypeMoniker Id="6a45fed8-1689-4fa9-8e39-f876365db554" LastKnownName="bool" />
                  </type_NamedElement>
                </parameter>
              </operationHasOwnedParameters>
            </ownedParameters>
          </operation>
          <operation Id="4456736b-d96f-41eb-aa5e-9569d0097bee" name="DelEmployee" isLeaf="false" isStatic="false" isAbstract="false" concurrency="Sequential" isQuery="false">
            <elementDefinition Id="108163b1-a848-42d6-a760-42034cdd4212" />
            <ownedParameters>
              <operationHasOwnedParameters>
                <parameter Id="55ba5296-f9a1-4084-9f29-2daa6e85a24c" direction="Return" isUnique="false">
                  <elementDefinition Id="cbdeb4f8-59d6-46cf-a42a-5c258112f9cc" />
                  <type_NamedElement>
                    <referencedTypeMoniker Id="6a45fed8-1689-4fa9-8e39-f876365db554" LastKnownName="bool" />
                  </type_NamedElement>
                </parameter>
              </operationHasOwnedParameters>
            </ownedParameters>
          </operation>
          <operation Id="3dc7ff2d-706b-4a80-b532-7bae7d12e4d0" name="GetMasterVisits" isLeaf="false" isStatic="false" isAbstract="false" concurrency="Sequential" isQuery="false">
            <elementDefinition Id="23b78fc1-c954-4f39-8724-6e9a7da0f8b3" />
            <ownedParameters>
              <operationHasOwnedParameters>
                <parameter Id="8b6fc5dd-251d-4c36-a419-b431b915f40c" direction="Return" isUnique="false">
                  <elementDefinition Id="1738fa02-c941-4caa-ad75-3b890ed9ab3c" />
                  <type_NamedElement>
                    <referencedTypeMoniker Id="b0b17692-ed70-44cf-ac5b-99a01cf9a1e6" LastKnownName="List&lt;Visit&gt;" />
                  </type_NamedElement>
                </parameter>
              </operationHasOwnedParameters>
            </ownedParameters>
          </operation>
          <operation Id="7ec01c2a-4990-4909-9c26-1167fc7c1434" name="CheckMasterCategory" isLeaf="false" isStatic="false" isAbstract="false" concurrency="Sequential" isQuery="false">
            <elementDefinition Id="66cf77a1-764b-4243-be7d-da684a1e05f6" />
            <ownedParameters>
              <operationHasOwnedParameters>
                <parameter Id="524f7643-f9c1-4ef5-8a1c-19e5180e7880" name="Category category" direction="In" isUnique="false">
                  <elementDefinition Id="d85af7cc-7976-40f7-9260-271fb79c1230" />
                </parameter>
              </operationHasOwnedParameters>
              <operationHasOwnedParameters>
                <parameter Id="3907ff5b-60a2-439e-88fa-e5bca5a42a0a" direction="Return" isUnique="false">
                  <elementDefinition Id="ba7b0851-350d-4798-8949-887ae5d8b476" />
                  <type_NamedElement>
                    <referencedTypeMoniker Id="6a45fed8-1689-4fa9-8e39-f876365db554" LastKnownName="bool" />
                  </type_NamedElement>
                </parameter>
              </operationHasOwnedParameters>
            </ownedParameters>
          </operation>
        </ownedOperationsInternal>
      </class>
    </logicalClassDesignerModelHasTypes>
    <logicalClassDesignerModelHasTypes>
      <class Id="9e4efbc8-78da-4018-bab1-5d0f33397b70" name="Employee {abstract}" isAbstract="true" isLeaf="false" isActiveClass="true">
        <elementDefinition Id="c5d92fcc-6b41-4682-ad1f-59437eebe00d" />
        <generalsInternal>
          <generalization Id="238bae82-e714-48fb-9013-a187ea1250b2" isSubstitutable="false">
            <classMoniker Id="eb5a3e5e-d4a7-4a33-abd3-e0b1cb37c416" LastKnownName="Person {abstract}" />
            <elementDefinition Id="f8f68a4a-f60d-4cca-9ad0-55f6f1ee1b0f" />
          </generalization>
        </generalsInternal>
        <targetEnds>
          <association Id="467275dd-1fc1-45de-8c06-3f79c17c3c0b" isDerived="false" sourceEndRoleName="Employee " targetEndRoleName="Workshop" isLeaf="false" isAbstract="false">
            <classMoniker Id="cd276153-9c6d-4ebc-b0d1-a6e2838d7c37" LastKnownName="Workshop" />
            <relationshipOwnedElementsInternal>
              <associationHasOwnedEnds>
                <memberEnd Id="73df3f04-237f-4e3a-afb5-07ffd405158e" name="Employee " isLeaf="false" isStatic="false" isReadOnly="false" isDerived="false" isDerivedUnion="false" aggregation="Composite" isComposite="false" isNavigableOwned="false">
                  <lowerValueInternal>
                    <literalString Id="21f8d754-fa49-4f0d-a276-e6e62dbac2ae" name="Lower" value="1">
                      <elementDefinition Id="2eaa3436-8611-48ce-bd91-8a2cf29fb976" />
                    </literalString>
                  </lowerValueInternal>
                  <upperValueInternal>
                    <literalString Id="c431c688-03cb-47db-9214-83152099ad9d" name="Upper" value="*">
                      <elementDefinition Id="fdea9952-a8c4-4504-9a0c-531a865939aa" />
                    </literalString>
                  </upperValueInternal>
                  <elementDefinition Id="ba75902b-6c44-4670-a106-3660d0ad1a5e" />
                </memberEnd>
              </associationHasOwnedEnds>
              <associationHasOwnedEnds>
                <memberEnd Id="b41299d0-f5d1-4831-9300-93e9250d45e5" name="Workshop" isLeaf="false" isStatic="false" isReadOnly="false" isDerived="false" isDerivedUnion="false" aggregation="None" isComposite="true">
                  <lowerValueInternal>
                    <literalString Id="091c15f2-1760-4531-ad5b-1d512daea63a" name="Lower" value="1">
                      <elementDefinition Id="9cdcedc5-5aef-4759-b9b8-b0d87a0bf842" />
                    </literalString>
                  </lowerValueInternal>
                  <upperValueInternal>
                    <literalString Id="13c2108b-4cf3-4e66-a5f4-1d9706c9be6d" name="Upper" value="1">
                      <elementDefinition Id="75bc8c21-dbbb-4cb5-82b3-c2ca814a5b7a" />
                    </literalString>
                  </upperValueInternal>
                  <elementDefinition Id="add34686-9115-4819-afc8-28800fa882df" />
                </memberEnd>
              </associationHasOwnedEnds>
            </relationshipOwnedElementsInternal>
            <elementDefinition Id="daf5b45f-c96b-48ef-a8c5-43008570634b" />
          </association>
          <association Id="75199914-125f-4e00-aa74-82e8e1065832" isDerived="false" sourceEndRoleName="Employee " targetEndRoleName="Role" isLeaf="false" isAbstract="false">
            <classMoniker Id="49e29943-c54c-45f2-9af3-97e7397fbc62" LastKnownName="Role" />
            <relationshipOwnedElementsInternal>
              <associationHasOwnedEnds>
                <memberEnd Id="c5a8e805-0e31-41a3-bdff-819ed17e8981" name="Employee " isLeaf="false" isStatic="false" isReadOnly="false" isDerived="false" isDerivedUnion="false" aggregation="Shared" isComposite="false" isNavigableOwned="false">
                  <lowerValueInternal>
                    <literalString Id="c2755e8a-67b1-4f23-90ad-5d241f7a52aa" name="Lower" value="1">
                      <elementDefinition Id="5704f2bb-7ddf-4a10-8b00-f22347a9dc6b" />
                    </literalString>
                  </lowerValueInternal>
                  <upperValueInternal>
                    <literalString Id="1788c323-5c25-40a7-a1a3-cfb72bd60cb8" name="Upper" value="*">
                      <elementDefinition Id="e57518cb-2fa7-4433-9afc-a38c4c28c706" />
                    </literalString>
                  </upperValueInternal>
                  <elementDefinition Id="9aea790f-4de0-41d3-b34d-fa23b3e9f001" />
                </memberEnd>
              </associationHasOwnedEnds>
              <associationHasOwnedEnds>
                <memberEnd Id="9b647329-0309-421f-a3fc-e25f2d4b8d7b" name="Role" isLeaf="false" isStatic="false" isReadOnly="false" isDerived="false" isDerivedUnion="false" aggregation="None" isComposite="false">
                  <elementDefinition Id="f4afb6e1-319f-4887-9966-932471195f73" />
                </memberEnd>
              </associationHasOwnedEnds>
            </relationshipOwnedElementsInternal>
            <elementDefinition Id="0702063c-4bf0-455c-aa56-e8c29d4e29a6" />
          </association>
        </targetEnds>
        <ownedAttributesInternal>
          <property Id="5707138f-b9d5-4fd2-ab47-318b3ffa3e70" name="Salary" isLeaf="false" isStatic="false" isReadOnly="false" isUnique="false" isDerived="false" isDerivedUnion="false" aggregation="None" isComposite="false">
            <elementDefinition Id="54d1ddef-9278-4e55-a6b1-a019b92ae152" />
            <type_NamedElement>
              <referencedTypeMoniker Id="b54dbda3-8339-49d3-8866-b7282104c16b" LastKnownName="decimal" />
            </type_NamedElement>
          </property>
          <property Id="e94c4edb-9e4f-4195-8ef7-1ca77baf4f80" name="AdditionalInfo" isLeaf="false" isStatic="false" isReadOnly="false" isUnique="false" isDerived="false" isDerivedUnion="false" aggregation="None" isComposite="false">
            <elementDefinition Id="50bea89b-7721-45e6-9504-fa5ec98414ee" />
            <type_NamedElement>
              <referencedTypeMoniker Id="35570a94-c851-4112-a001-af83a52859c2" LastKnownName="String" />
            </type_NamedElement>
          </property>
          <property Id="d8b30267-640c-456c-a274-cea2102e7062" name="Password" isLeaf="false" isStatic="false" isReadOnly="false" isUnique="false" isDerived="false" isDerivedUnion="false" aggregation="None" isComposite="false">
            <elementDefinition Id="89f88675-e207-4285-a43a-181ecc06605b" />
            <type_NamedElement>
              <referencedTypeMoniker Id="97109223-dea9-4033-bc34-c1195d82749b" LastKnownName="String" />
            </type_NamedElement>
          </property>
          <property Id="030fb0b0-70b8-49a5-94ab-7628b4208c15" name="Workshop" isLeaf="false" isStatic="false" isReadOnly="false" isUnique="false" isDerived="false" isDerivedUnion="false" aggregation="None" isComposite="false">
            <elementDefinition Id="59236aed-9ee4-48d3-8613-bc08591515eb" />
            <type_NamedElement>
              <referencedTypeMoniker Id="f4c65483-48fa-48c6-b1ba-774306746da9" LastKnownName="Workshop" />
            </type_NamedElement>
          </property>
          <property Id="e1d512ad-1269-4db4-b6b3-5bee54d8eae7" name="Role" isLeaf="false" isStatic="false" isReadOnly="false" isUnique="false" isDerived="false" isDerivedUnion="false" aggregation="None" isComposite="false">
            <elementDefinition Id="04771391-feab-4198-928f-94371aca1b47" />
            <type_NamedElement>
              <referencedTypeMoniker Id="dcabf460-1745-43b0-bd60-733bb6dd04c2" LastKnownName="Role" />
            </type_NamedElement>
          </property>
        </ownedAttributesInternal>
        <ownedOperationsInternal>
          <operation Id="91248267-0172-4281-96ff-98fdb20c73c6" name="GetTimetable" isLeaf="false" isStatic="false" isAbstract="false" concurrency="Sequential" isQuery="false">
            <elementDefinition Id="7d338f7e-281e-4523-a545-f0f0a5940bac" />
            <ownedParameters>
              <operationHasOwnedParameters>
                <parameter Id="a78040b6-abfd-4580-a68c-e5acdb62a66d" direction="Return" isUnique="false">
                  <elementDefinition Id="06cca432-a3d2-40b1-80fc-09c607949cdc" />
                  <type_NamedElement>
                    <referencedTypeMoniker Id="b226682f-730a-40bb-be1b-9ad80cd255ed" LastKnownName="List&lt;EmployeeTimetable&gt;" />
                  </type_NamedElement>
                </parameter>
              </operationHasOwnedParameters>
              <operationHasOwnedParameters>
                <parameter Id="a4c014b7-9a8b-4285-ac12-5a53232d48e3" name="page" direction="In" isUnique="false">
                  <elementDefinition Id="b7d29b88-1e5c-4939-9d60-9f07c485cf00" />
                  <type_NamedElement>
                    <referencedTypeMoniker Id="de578a74-cb65-4d29-833c-4c0b903c29db" LastKnownName="int" />
                  </type_NamedElement>
                </parameter>
              </operationHasOwnedParameters>
              <operationHasOwnedParameters>
                <parameter Id="7051a0c9-fc64-4943-af93-4ac7ae940448" name="count" direction="In" isUnique="false">
                  <elementDefinition Id="dfec3ad3-1006-4dd2-82fc-4599ff8547b7" />
                  <type_NamedElement>
                    <referencedTypeMoniker Id="de578a74-cb65-4d29-833c-4c0b903c29db" LastKnownName="int" />
                  </type_NamedElement>
                </parameter>
              </operationHasOwnedParameters>
              <operationHasOwnedParameters>
                <parameter Id="373730f1-d27f-43e0-a8eb-4f93ec67370c" name="from" direction="In" isUnique="false">
                  <elementDefinition Id="e57ccf98-cbd1-4ac0-b047-79478b863605" />
                </parameter>
              </operationHasOwnedParameters>
              <operationHasOwnedParameters>
                <parameter Id="bcb61319-4ab5-4719-b979-61febafbe495" direction="In" isUnique="false">
                  <elementDefinition Id="bf7f0914-06cb-4a00-b764-32893ad4b0ae" />
                  <type_NamedElement>
                    <referencedTypeMoniker Id="5e95a766-896f-41c7-8951-778ddf708d7a" LastKnownName="DateTime" />
                  </type_NamedElement>
                </parameter>
              </operationHasOwnedParameters>
              <operationHasOwnedParameters>
                <parameter Id="b1b280c1-e8cf-4284-97a7-f979cd69734a" name="until" direction="In" isUnique="false">
                  <elementDefinition Id="a4df3389-6a4a-414a-8378-169892fa0fa4" />
                  <type_NamedElement>
                    <referencedTypeMoniker Id="5e95a766-896f-41c7-8951-778ddf708d7a" LastKnownName="DateTime" />
                  </type_NamedElement>
                </parameter>
              </operationHasOwnedParameters>
            </ownedParameters>
          </operation>
          <operation Id="3189ac1e-1a72-47a8-9a8a-dba36ac7b3df" name="AddEmployee" isLeaf="false" isStatic="false" isAbstract="false" concurrency="Sequential" isQuery="false">
            <elementDefinition Id="e3425e68-fdf7-4572-af44-740c6b372c7c" />
            <ownedParameters>
              <operationHasOwnedParameters>
                <parameter Id="0ad10fcf-8117-48a4-9366-6894cfe15a2b" direction="Return" isUnique="false">
                  <elementDefinition Id="31e4782e-0f37-48fe-b8f1-91093f04b6fa" />
                  <type_NamedElement>
                    <referencedTypeMoniker Id="6a45fed8-1689-4fa9-8e39-f876365db554" LastKnownName="bool" />
                  </type_NamedElement>
                </parameter>
              </operationHasOwnedParameters>
            </ownedParameters>
          </operation>
          <operation Id="4a3c9323-9f4c-4836-8988-a0453ad857f9" name="DelEmployee" isLeaf="false" isStatic="false" isAbstract="false" concurrency="Sequential" isQuery="false">
            <elementDefinition Id="2eacce2c-ff9a-44e0-940f-fe2e18184cd1" />
            <ownedParameters>
              <operationHasOwnedParameters>
                <parameter Id="cc91d966-db59-4688-8c23-43b01a5e66d4" direction="Return" isUnique="false">
                  <elementDefinition Id="640fd557-cd21-409a-ad14-138372260ca6" />
                  <type_NamedElement>
                    <referencedTypeMoniker Id="6a45fed8-1689-4fa9-8e39-f876365db554" LastKnownName="bool" />
                  </type_NamedElement>
                </parameter>
              </operationHasOwnedParameters>
            </ownedParameters>
          </operation>
          <operation Id="a972b040-c4cd-4508-ab09-dfc350bff176" name="EditEmployee" isLeaf="false" isStatic="false" isAbstract="false" concurrency="Sequential" isQuery="false">
            <elementDefinition Id="7876d5ca-648d-47cc-a9e6-1ddb6cad0b5d" />
            <ownedParameters>
              <operationHasOwnedParameters>
                <parameter Id="65c3179a-f8d0-4bc3-86e0-b972a49ec9bc" direction="Return" isUnique="false">
                  <elementDefinition Id="fc5cb003-3dd6-47f5-85c7-6b3108b87feb" />
                  <type_NamedElement>
                    <referencedTypeMoniker Id="6a45fed8-1689-4fa9-8e39-f876365db554" LastKnownName="bool" />
                  </type_NamedElement>
                </parameter>
              </operationHasOwnedParameters>
            </ownedParameters>
          </operation>
        </ownedOperationsInternal>
      </class>
    </logicalClassDesignerModelHasTypes>
    <logicalClassDesignerModelHasTypes>
      <class Id="b6856be0-2a50-4617-a0c0-c385060eb4f9" name="Manager" isAbstract="false" isLeaf="false" isActiveClass="false">
        <elementDefinition Id="7185b57f-ed0d-487e-a875-3d0c08bdef1f" />
        <generalsInternal>
          <generalization Id="232d7c15-f9e3-45d8-b9e1-dca99d1c910d" isSubstitutable="false">
            <classMoniker Id="9e4efbc8-78da-4018-bab1-5d0f33397b70" LastKnownName="Employee {abstract}" />
            <elementDefinition Id="5b98e868-2580-49ff-ba53-2ad01b1a56f6" />
          </generalization>
        </generalsInternal>
        <ownedAttributesInternal>
          <property Id="ee135f4a-199b-4139-813b-80b1be30973f" name="Remotely" isLeaf="false" isStatic="false" isReadOnly="false" isUnique="false" isDerived="false" isDerivedUnion="false" aggregation="None" isComposite="false">
            <elementDefinition Id="e3a9cb9e-ce45-4529-a682-8d8f9b197c23" />
            <type_NamedElement>
              <referencedTypeMoniker Id="6a45fed8-1689-4fa9-8e39-f876365db554" LastKnownName="bool" />
            </type_NamedElement>
          </property>
        </ownedAttributesInternal>
        <ownedOperationsInternal>
          <operation Id="65d89551-36c4-4f61-8f51-cf18ae7a455b" name="Manager" isLeaf="false" isStatic="false" isAbstract="false" concurrency="Sequential" isQuery="false">
            <elementDefinition Id="f2e8025b-9009-4cbe-b324-45f2f889c7dd" />
            <ownedParameters>
              <operationHasOwnedParameters>
                <parameter Id="0c18cfb9-ef84-4263-a2c5-f0adaac57793" direction="Return" isUnique="false">
                  <elementDefinition Id="eb90f90c-a6a1-4233-a7f4-d7e68667c828" />
                  <type_NamedElement>
                    <referencedTypeMoniker Id="62e1c591-1fc8-4d49-889d-ba3d80faa959" LastKnownName="void" />
                  </type_NamedElement>
                </parameter>
              </operationHasOwnedParameters>
            </ownedParameters>
          </operation>
          <operation Id="9c11cb6d-b1bf-4f37-b5e3-971e9c8853df" name="AddEmployee" isLeaf="false" isStatic="false" isAbstract="false" concurrency="Sequential" isQuery="false">
            <elementDefinition Id="d069ec92-18e6-4ac5-a41a-8938d32aee1a" />
            <ownedParameters>
              <operationHasOwnedParameters>
                <parameter Id="43f73fab-a699-4395-bad5-ba5b23287d05" direction="Return" isUnique="false">
                  <elementDefinition Id="cd6da1cb-aa2a-4724-9761-319ed61f0f7e" />
                  <type_NamedElement>
                    <referencedTypeMoniker Id="6a45fed8-1689-4fa9-8e39-f876365db554" LastKnownName="bool" />
                  </type_NamedElement>
                </parameter>
              </operationHasOwnedParameters>
            </ownedParameters>
          </operation>
          <operation Id="3f2faa61-eed3-4084-a7e5-10f4d4f39291" name="DelEmployee" isLeaf="false" isStatic="false" isAbstract="false" concurrency="Sequential" isQuery="false">
            <elementDefinition Id="a0bf431f-f527-4a10-99c4-eb2610d6ee0e" />
            <ownedParameters>
              <operationHasOwnedParameters>
                <parameter Id="fa2ee3af-65aa-4d50-a522-53bb9ac3228e" direction="Return" isUnique="false">
                  <elementDefinition Id="80a271e6-b72c-4f49-992b-2b555de5c223" />
                  <type_NamedElement>
                    <referencedTypeMoniker Id="6a45fed8-1689-4fa9-8e39-f876365db554" LastKnownName="bool" />
                  </type_NamedElement>
                </parameter>
              </operationHasOwnedParameters>
            </ownedParameters>
          </operation>
          <operation Id="fca7eb91-514b-4997-8ca3-940640b17aba" name="EditEmployee" isLeaf="false" isStatic="false" isAbstract="false" concurrency="Sequential" isQuery="false">
            <elementDefinition Id="3b22b3fd-ae87-4d5c-8626-8fcdf15c5191" />
            <ownedParameters>
              <operationHasOwnedParameters>
                <parameter Id="18eea84c-0366-4fc2-bf4c-f4b85562680a" direction="Return" isUnique="false">
                  <elementDefinition Id="c6e39567-bc1d-4a64-80a6-25a597ccecd7" />
                  <type_NamedElement>
                    <referencedTypeMoniker Id="6a45fed8-1689-4fa9-8e39-f876365db554" LastKnownName="bool" />
                  </type_NamedElement>
                </parameter>
              </operationHasOwnedParameters>
            </ownedParameters>
          </operation>
        </ownedOperationsInternal>
      </class>
    </logicalClassDesignerModelHasTypes>
    <logicalClassDesignerModelHasTypes>
      <class Id="ecb68bbe-7ceb-4436-a662-49d34c98b121" name="Category" isAbstract="false" isLeaf="false" isActiveClass="false">
        <elementDefinition Id="727e2bd1-9ffe-4f58-a321-0a671237657e" />
        <ownedAttributesInternal>
          <property Id="5aca76a6-6b88-4f4c-a624-3439db71ca70" name="Name" isLeaf="false" isStatic="false" isReadOnly="false" isUnique="false" isDerived="false" isDerivedUnion="false" aggregation="None" isComposite="false">
            <elementDefinition Id="fc192510-fcd3-4218-8a65-40db5073919d" />
            <type_NamedElement>
              <referencedTypeMoniker Id="40ded824-e2e4-49f3-98b4-8924991947eb" LastKnownName="String" />
            </type_NamedElement>
          </property>
          <property Id="04157d11-33bc-4118-92fd-7842ea56f53f" name="id" isLeaf="false" isStatic="false" isReadOnly="false" isUnique="false" isDerived="false" isDerivedUnion="false" aggregation="None" isComposite="false">
            <elementDefinition Id="7d487109-3db7-4d55-a252-7d048b2e4885" />
            <type_NamedElement>
              <referencedTypeMoniker Id="38004bd3-1664-4fea-bd7a-a5c72cb72550" LastKnownName="Integer" />
            </type_NamedElement>
          </property>
          <property Id="eda84720-25ef-4345-a4e1-60cb96da1977" name="ParentCategory" isLeaf="false" isStatic="false" isReadOnly="false" isUnique="false" isDerived="false" isDerivedUnion="false" aggregation="None" isComposite="false">
            <elementDefinition Id="290f5109-b7c4-4117-8ae9-dc4eaa34f26f" />
            <type_NamedElement>
              <referencedTypeMoniker Id="6c593322-0955-41a8-b52b-79af32acfbe4" LastKnownName="Category" />
            </type_NamedElement>
          </property>
          <property Id="eef8baf8-4d40-4046-957d-5657c5ff9a91" name="DelTime" isLeaf="false" isStatic="false" isReadOnly="false" isUnique="false" isDerived="false" isDerivedUnion="false" aggregation="None" isComposite="false">
            <elementDefinition Id="891629fd-e345-4471-bb9e-b2994dbde71f" />
            <type_NamedElement>
              <referencedTypeMoniker Id="5e95a766-896f-41c7-8951-778ddf708d7a" LastKnownName="DateTime" />
            </type_NamedElement>
          </property>
        </ownedAttributesInternal>
        <ownedOperationsInternal>
          <operation Id="10dbb890-d1fb-4b5e-b5c4-6ecf7a53a614" name="Category" isLeaf="false" isStatic="false" isAbstract="false" concurrency="Sequential" isQuery="false">
            <elementDefinition Id="67e1134f-9fe5-435d-818a-1d208be361b2" />
            <ownedParameters>
              <operationHasOwnedParameters>
                <parameter Id="3d4d7af5-19c1-4b36-b692-490a2157200b" direction="Return" isUnique="false">
                  <elementDefinition Id="a1e8f5ca-5fd3-4032-97b6-45b49b35d4f7" />
                  <type_NamedElement>
                    <referencedTypeMoniker Id="62e1c591-1fc8-4d49-889d-ba3d80faa959" LastKnownName="void" />
                  </type_NamedElement>
                </parameter>
              </operationHasOwnedParameters>
            </ownedParameters>
          </operation>
          <operation Id="56e260f1-7645-47a3-9da7-ea7698c3a827" name="AddCategory" isLeaf="false" isStatic="false" isAbstract="false" concurrency="Sequential" isQuery="false">
            <elementDefinition Id="3724eeb2-728e-4bb3-be78-be145d0f77d2" />
            <ownedParameters>
              <operationHasOwnedParameters>
                <parameter Id="606d4a24-069a-4045-ab75-31115ab76994" direction="Return" isUnique="false">
                  <elementDefinition Id="9ac60d00-08e8-40ee-9a97-1dce0a4681e3" />
                  <type_NamedElement>
                    <referencedTypeMoniker Id="6a45fed8-1689-4fa9-8e39-f876365db554" LastKnownName="bool" />
                  </type_NamedElement>
                </parameter>
              </operationHasOwnedParameters>
            </ownedParameters>
          </operation>
          <operation Id="68d4e57c-f7e3-4691-9088-d14f093afa27" name="DelCategory" isLeaf="false" isStatic="false" isAbstract="false" concurrency="Sequential" isQuery="false">
            <elementDefinition Id="8885e0df-1694-4307-873c-03843fd72786" />
            <ownedParameters>
              <operationHasOwnedParameters>
                <parameter Id="09973d5d-fe08-4045-b685-2bdd47cd6cd3" direction="Return" isUnique="false">
                  <elementDefinition Id="510e1b95-68eb-4d7a-b369-d6123f71d94d" />
                  <type_NamedElement>
                    <referencedTypeMoniker Id="8f053d6a-4a26-47f8-9af2-662245598a78" LastKnownName="bool" />
                  </type_NamedElement>
                </parameter>
              </operationHasOwnedParameters>
            </ownedParameters>
          </operation>
          <operation Id="3615aea9-e249-4357-b66c-b2b62ccd72b9" name="EditCategory" isLeaf="false" isStatic="false" isAbstract="false" concurrency="Sequential" isQuery="false">
            <elementDefinition Id="4068e6a9-1100-4dc3-a743-362f5ffa2ec6" />
            <ownedParameters>
              <operationHasOwnedParameters>
                <parameter Id="e662d0cc-135d-4004-889e-25dd1f96cea9" direction="Return" isUnique="false">
                  <elementDefinition Id="64fc4352-8d74-4abf-951d-dd7b1e149015" />
                  <type_NamedElement>
                    <referencedTypeMoniker Id="6a45fed8-1689-4fa9-8e39-f876365db554" LastKnownName="bool" />
                  </type_NamedElement>
                </parameter>
              </operationHasOwnedParameters>
            </ownedParameters>
          </operation>
          <operation Id="35a869ff-54ab-49fe-9f0c-930733bc3698" name="GetParents" isLeaf="false" isStatic="false" isAbstract="false" concurrency="Sequential" isQuery="false">
            <elementDefinition Id="d9198511-a80c-4650-a8ca-58a4b968fec9" />
            <ownedParameters>
              <operationHasOwnedParameters>
                <parameter Id="63afeb9c-7099-4ea1-8e34-20f7c8ae82ee" direction="Return" isUnique="false">
                  <elementDefinition Id="bd599c35-d0b8-40ca-a6e5-b45706925629" />
                  <type_NamedElement>
                    <referencedTypeMoniker Id="d196a296-ba5f-447c-b890-b886fcfbc7a4" LastKnownName="List&lt;Category&gt;" />
                  </type_NamedElement>
                </parameter>
              </operationHasOwnedParameters>
            </ownedParameters>
          </operation>
          <operation Id="1f0c92a4-02b5-476e-95f7-a40329c0676c" name="GetWholeBranch" isLeaf="false" isStatic="false" isAbstract="false" concurrency="Sequential" isQuery="false">
            <elementDefinition Id="94141040-77eb-44b2-832b-8e4e993356ec" />
            <ownedParameters>
              <operationHasOwnedParameters>
                <parameter Id="edc4eadf-93de-47b8-8d32-d85d61d539b2" direction="Return" isUnique="false">
                  <elementDefinition Id="7bdedda3-1ac0-42af-b71f-3fd76a78d0b5" />
                  <type_NamedElement>
                    <referencedTypeMoniker Id="d196a296-ba5f-447c-b890-b886fcfbc7a4" LastKnownName="List&lt;Category&gt;" />
                  </type_NamedElement>
                </parameter>
              </operationHasOwnedParameters>
            </ownedParameters>
          </operation>
        </ownedOperationsInternal>
      </class>
    </logicalClassDesignerModelHasTypes>
    <packageHasNamedElement>
      <referencedType Id="38004bd3-1664-4fea-bd7a-a5c72cb72550" name="Integer" isAbstract="false" isLeaf="false" cachedFullName="Integer">
        <elementDefinition Id="220a3521-e091-4221-bae9-3ef9018e845c" />
      </referencedType>
    </packageHasNamedElement>
    <packageHasNamedElement>
      <referencedType Id="40ded824-e2e4-49f3-98b4-8924991947eb" name="String" isAbstract="false" isLeaf="false" cachedFullName="String">
        <elementDefinition Id="59259974-6d55-42c6-b7bd-763d77ac8ef9" />
      </referencedType>
    </packageHasNamedElement>
    <packageHasNamedElement>
      <referencedType Id="97109223-dea9-4033-bc34-c1195d82749b" name="String" isAbstract="false" isLeaf="false" cachedFullName="String">
        <elementDefinition Id="59259974-6d55-42c6-b7bd-763d77ac8ef9" />
      </referencedType>
    </packageHasNamedElement>
    <logicalClassDesignerModelHasTypes>
      <class Id="9b4b7581-ed32-482e-b87e-80fb21168b7b" name="Product" isAbstract="false" isLeaf="false" isActiveClass="false">
        <elementDefinition Id="57480d6f-b872-4e75-b996-e8207e616f49" />
        <targetEnds>
          <association Id="ca3c478d-c8e7-4295-b80e-7d5cc73543f7" isDerived="false" sourceEndRoleName="Product" targetEndRoleName="Categorie" isLeaf="false" isAbstract="false">
            <classMoniker Id="ecb68bbe-7ceb-4436-a662-49d34c98b121" LastKnownName="Category" />
            <relationshipOwnedElementsInternal>
              <associationHasOwnedEnds>
                <memberEnd Id="3533b83a-2053-4983-a156-073c9e8f92ee" name="Product" isLeaf="false" isStatic="false" isReadOnly="false" isDerived="false" isDerivedUnion="false" aggregation="Composite" isComposite="false" isNavigableOwned="false">
                  <lowerValueInternal>
                    <literalString Id="3e7d64f0-db88-4833-823b-d144a14679a5" name="Lower" value="0">
                      <elementDefinition Id="37c7c750-5fa8-4469-a10a-1f275324da6d" />
                    </literalString>
                  </lowerValueInternal>
                  <upperValueInternal>
                    <literalString Id="b59c5e06-0a30-4cea-8025-67a9d463851a" name="Upper" value="*">
                      <elementDefinition Id="4ecf1cff-c110-4210-b3f1-221250071fcc" />
                    </literalString>
                  </upperValueInternal>
                  <elementDefinition Id="1c10dd57-d80f-435c-a9e1-e69c4e0e2dd0" />
                </memberEnd>
              </associationHasOwnedEnds>
              <associationHasOwnedEnds>
                <memberEnd Id="aba4a663-e530-48bb-be16-9b85cafc1b03" name="Categorie" isLeaf="false" isStatic="false" isReadOnly="false" isDerived="false" isDerivedUnion="false" aggregation="None" isComposite="true">
                  <elementDefinition Id="5077a162-c686-4baa-92dc-8c7662c55e31" />
                </memberEnd>
              </associationHasOwnedEnds>
            </relationshipOwnedElementsInternal>
            <elementDefinition Id="1f6b807a-24e8-472d-93a0-a4fbf5cefc05" />
          </association>
          <association Id="c9a92489-da4b-4a1a-9668-bfa6e54e4ab1" isDerived="false" sourceEndRoleName="Product" targetEndRoleName="Client" isLeaf="false" isAbstract="false">
            <classMoniker Id="a5c00f8f-2e99-4e50-af3d-5016ef70a856" LastKnownName="Client" />
            <relationshipOwnedElementsInternal>
              <associationHasOwnedEnds>
                <memberEnd Id="15ba95e4-6dc5-42aa-9243-de7ce21443f9" name="Product" isLeaf="false" isStatic="false" isReadOnly="false" isDerived="false" isDerivedUnion="false" aggregation="Composite" isComposite="false" isNavigableOwned="false">
                  <lowerValueInternal>
                    <literalString Id="4cc6235a-bd8f-4638-aa22-cc124123e052" name="Lower" value="0">
                      <elementDefinition Id="41ae1394-7598-43c0-b4d0-e72a0fa4a6f3" />
                    </literalString>
                  </lowerValueInternal>
                  <upperValueInternal>
                    <literalString Id="93e5928f-f694-425b-a2eb-cdfeab641c9c" name="Upper" value="*">
                      <elementDefinition Id="5f80331c-d9f7-4749-a6dd-03191ba2763f" />
                    </literalString>
                  </upperValueInternal>
                  <elementDefinition Id="b8c3d88b-bf09-41e4-a1a7-d05b9e2850d9" />
                </memberEnd>
              </associationHasOwnedEnds>
              <associationHasOwnedEnds>
                <memberEnd Id="97b0e5ff-c9a7-44f9-b71b-709d14e06d28" name="Client" isLeaf="false" isStatic="false" isReadOnly="false" isDerived="false" isDerivedUnion="false" aggregation="None" isComposite="true">
                  <elementDefinition Id="9ab22fc0-17dc-49b7-890f-865922863365" />
                </memberEnd>
              </associationHasOwnedEnds>
            </relationshipOwnedElementsInternal>
            <elementDefinition Id="54d18924-9972-47e6-8d14-f3663a34730b" />
          </association>
        </targetEnds>
        <ownedAttributesInternal>
          <property Id="32e51625-ee73-4120-9b92-780e07252cac" name="id" isLeaf="false" isStatic="false" isReadOnly="false" isUnique="false" isDerived="false" isDerivedUnion="false" aggregation="None" isComposite="false">
            <elementDefinition Id="fe15d4e6-d654-4fc6-8d25-eb2bab2c6c75" />
            <type_NamedElement>
              <referencedTypeMoniker Id="c32905f0-79ed-46da-8ad8-cb146a72cb38" LastKnownName="Integer" />
            </type_NamedElement>
          </property>
          <property Id="94ca2554-ad9a-4dc8-97db-2c26fd9f1723" name="Name" isLeaf="false" isStatic="false" isReadOnly="false" isUnique="false" isDerived="false" isDerivedUnion="false" aggregation="None" isComposite="false">
            <elementDefinition Id="cf35c119-49c5-4607-b54c-bf2ad9ad1c27" />
            <type_NamedElement>
              <referencedTypeMoniker Id="46a6a608-0aec-4ac5-a8eb-5f3f1db84b4a" LastKnownName="String" />
            </type_NamedElement>
          </property>
          <property Id="deeb01d4-57e6-4c08-ac85-7f5086ac7f83" name="Caregory" isLeaf="false" isStatic="false" isReadOnly="false" isUnique="false" isDerived="false" isDerivedUnion="false" aggregation="None" isComposite="false">
            <elementDefinition Id="c86166fa-4f55-47d0-b1d1-b4a67bb6bd4e" />
            <type_NamedElement>
              <referencedTypeMoniker Id="216ec45d-0959-4ce1-9479-89588bab40bd" LastKnownName="Category" />
            </type_NamedElement>
          </property>
          <property Id="552f25a4-2f79-421a-8149-c9993089f341" name="Cliet" isLeaf="false" isStatic="false" isReadOnly="false" isUnique="false" isDerived="false" isDerivedUnion="false" aggregation="None" isComposite="false">
            <elementDefinition Id="2189e60d-0f40-4b41-8912-5185146de4d3" />
            <type_NamedElement>
              <referencedTypeMoniker Id="8171f1a1-2c1e-465d-9bbc-4fb55940dca2" LastKnownName="Client" />
            </type_NamedElement>
          </property>
          <property Id="5dfe2d3f-e195-4aec-a5cd-8c944019cda2" name="DelTime" isLeaf="false" isStatic="false" isReadOnly="false" isUnique="false" isDerived="false" isDerivedUnion="false" aggregation="None" isComposite="false">
            <elementDefinition Id="c23da8f4-1035-4ede-8df5-385425dc045d" />
            <type_NamedElement>
              <referencedTypeMoniker Id="5e95a766-896f-41c7-8951-778ddf708d7a" LastKnownName="DateTime" />
            </type_NamedElement>
          </property>
        </ownedAttributesInternal>
        <ownedOperationsInternal>
          <operation Id="b8b079f4-767c-48a6-820d-19a1b4a1fd5e" name="Product" isLeaf="false" isStatic="false" isAbstract="false" concurrency="Sequential" isQuery="false">
            <elementDefinition Id="16b7143c-2015-4a03-bdb0-c9c0ffcb959d" />
            <ownedParameters>
              <operationHasOwnedParameters>
                <parameter Id="06d02879-6f99-4e3e-b542-af8949edf076" direction="Return" isUnique="false">
                  <elementDefinition Id="b4bcb6d5-0779-4e05-b967-0193866a7df9" />
                  <type_NamedElement>
                    <referencedTypeMoniker Id="62e1c591-1fc8-4d49-889d-ba3d80faa959" LastKnownName="void" />
                  </type_NamedElement>
                </parameter>
              </operationHasOwnedParameters>
            </ownedParameters>
          </operation>
          <operation Id="28e46a4c-0d58-43c1-80b2-bf2b840bbbda" name="AddProduct" isLeaf="false" isStatic="false" isAbstract="false" concurrency="Sequential" isQuery="false">
            <elementDefinition Id="db31590b-537f-4d0c-9fd8-1019959dc24a" />
            <ownedParameters>
              <operationHasOwnedParameters>
                <parameter Id="9b383aa7-ae91-4359-8a2a-de3e9bd29b4a" direction="Return" isUnique="false">
                  <elementDefinition Id="ac57c495-7311-45fb-be8e-482f74b4777b" />
                  <type_NamedElement>
                    <referencedTypeMoniker Id="6a45fed8-1689-4fa9-8e39-f876365db554" LastKnownName="bool" />
                  </type_NamedElement>
                </parameter>
              </operationHasOwnedParameters>
            </ownedParameters>
          </operation>
          <operation Id="bd3da5ef-bbdb-4dfa-9938-b787947a7015" name="DelProduct" isLeaf="false" isStatic="false" isAbstract="false" concurrency="Sequential" isQuery="false">
            <elementDefinition Id="ed9c4e2f-106b-4058-85de-791ec6f43c68" />
            <ownedParameters>
              <operationHasOwnedParameters>
                <parameter Id="ce736013-d770-4803-b113-7034bf097393" direction="Return" isUnique="false">
                  <elementDefinition Id="efad7fc0-1a3d-4536-b215-c22d92aca7f4" />
                  <type_NamedElement>
                    <referencedTypeMoniker Id="6a45fed8-1689-4fa9-8e39-f876365db554" LastKnownName="bool" />
                  </type_NamedElement>
                </parameter>
              </operationHasOwnedParameters>
            </ownedParameters>
          </operation>
          <operation Id="29513283-dc46-41b5-acdf-a7efcecf98a9" name="EditProduct" isLeaf="false" isStatic="false" isAbstract="false" concurrency="Sequential" isQuery="false">
            <elementDefinition Id="0258fe81-1914-4dbd-ad98-b82a759e9ab1" />
            <ownedParameters>
              <operationHasOwnedParameters>
                <parameter Id="870b1ea3-cdcf-4c69-9ca6-ee959702f7ff" direction="Return" isUnique="false">
                  <elementDefinition Id="df580385-4dca-4156-ab37-297ea9a9ee41" />
                  <type_NamedElement>
                    <referencedTypeMoniker Id="6a45fed8-1689-4fa9-8e39-f876365db554" LastKnownName="bool" />
                  </type_NamedElement>
                </parameter>
              </operationHasOwnedParameters>
            </ownedParameters>
          </operation>
        </ownedOperationsInternal>
      </class>
    </logicalClassDesignerModelHasTypes>
    <packageHasNamedElement>
      <referencedType Id="c32905f0-79ed-46da-8ad8-cb146a72cb38" name="Integer" isAbstract="false" isLeaf="false" cachedFullName="Integer">
        <elementDefinition Id="220a3521-e091-4221-bae9-3ef9018e845c" />
      </referencedType>
    </packageHasNamedElement>
    <packageHasNamedElement>
      <referencedType Id="46a6a608-0aec-4ac5-a8eb-5f3f1db84b4a" name="String" isAbstract="false" isLeaf="false" cachedFullName="String">
        <elementDefinition Id="59259974-6d55-42c6-b7bd-763d77ac8ef9" />
      </referencedType>
    </packageHasNamedElement>
    <packageHasNamedElement>
      <referencedType Id="6c593322-0955-41a8-b52b-79af32acfbe4" name="Category" isAbstract="false" isLeaf="false" cachedFullName="CompServiceClassDiagram::Category">
        <elementDefinition Id="727e2bd1-9ffe-4f58-a321-0a671237657e" />
      </referencedType>
    </packageHasNamedElement>
    <logicalClassDesignerModelHasTypes>
      <class Id="60a4334c-dbe6-43a7-b0f6-19e3f89831ed" name="Service" isAbstract="false" isLeaf="false" isActiveClass="false">
        <elementDefinition Id="b0c4b702-5e5a-4e3c-8cd4-918150c7b380" />
        <targetEnds>
          <association Id="3b226631-9828-4848-a8e0-1463f864871c" isDerived="false" sourceEndRoleName="Service" targetEndRoleName="Categorie" isLeaf="false" isAbstract="false">
            <classMoniker Id="ecb68bbe-7ceb-4436-a662-49d34c98b121" LastKnownName="Category" />
            <relationshipOwnedElementsInternal>
              <associationHasOwnedEnds>
                <memberEnd Id="2e94bddf-3709-4dae-bf1e-ef8b78c2fc6e" name="Service" isLeaf="false" isStatic="false" isReadOnly="false" isDerived="false" isDerivedUnion="false" aggregation="Composite" isComposite="false" isNavigableOwned="false">
                  <lowerValueInternal>
                    <literalString Id="2cd62201-d4e7-4e5d-9a28-bb00e531f236" name="Lower" value="1">
                      <elementDefinition Id="0a58be6c-a5ad-4876-b83b-c3c24617b97f" />
                    </literalString>
                  </lowerValueInternal>
                  <upperValueInternal>
                    <literalString Id="38c2c2e3-7d00-41ea-abf6-e44006c52f93" name="Upper" value="*">
                      <elementDefinition Id="edb359e5-3e25-47e9-9681-29a3c0ff61c1" />
                    </literalString>
                  </upperValueInternal>
                  <elementDefinition Id="d64e88aa-7198-4012-8113-03c7eded6498" />
                </memberEnd>
              </associationHasOwnedEnds>
              <associationHasOwnedEnds>
                <memberEnd Id="ede9f86b-bea5-47ed-a4fc-3b829f4e19e7" name="Categorie" isLeaf="false" isStatic="false" isReadOnly="false" isDerived="false" isDerivedUnion="false" aggregation="None" isComposite="true">
                  <lowerValueInternal>
                    <literalString Id="127d8406-4afe-4e0e-94b9-9c88a3ff07f7" name="Lower" value="1">
                      <elementDefinition Id="a24e2f27-b5c6-4acb-a424-e141e7521d1c" />
                    </literalString>
                  </lowerValueInternal>
                  <upperValueInternal>
                    <literalString Id="7e7335e5-7610-416e-9574-d017ccbfb1e7" name="Upper" value="1">
                      <elementDefinition Id="2f01e116-51a1-4150-b2a6-7b31a97a310f" />
                    </literalString>
                  </upperValueInternal>
                  <elementDefinition Id="9e7cf172-b218-4ad3-b70a-8360dac628d3" />
                </memberEnd>
              </associationHasOwnedEnds>
            </relationshipOwnedElementsInternal>
            <elementDefinition Id="bd24918e-d647-4c81-8a5d-b5bc3cd34d0e" />
          </association>
        </targetEnds>
        <ownedAttributesInternal>
          <property Id="ae0707e3-35bf-4238-9beb-35ff26dfe273" name="Name" isLeaf="false" isStatic="false" isReadOnly="false" isUnique="false" isDerived="false" isDerivedUnion="false" aggregation="None" isComposite="false">
            <elementDefinition Id="447b0182-1206-4982-82cb-3fcd1dad76fe" />
            <type_NamedElement>
              <referencedTypeMoniker Id="056c53aa-cdd8-46ea-98df-0259d1a4b020" LastKnownName="String" />
            </type_NamedElement>
          </property>
          <property Id="f43b40a4-8c7f-4420-be97-39b2f563893a" name="id" isLeaf="false" isStatic="false" isReadOnly="false" isUnique="false" isDerived="false" isDerivedUnion="false" aggregation="None" isComposite="false">
            <elementDefinition Id="5ee9a243-3950-4e12-ac2a-caadbdcd3546" />
            <type_NamedElement>
              <referencedTypeMoniker Id="f0f44efc-4066-4ed3-9ddd-5070b9ce1adb" LastKnownName="Integer" />
            </type_NamedElement>
          </property>
          <property Id="3b2ea09c-0d0e-4302-b631-ba6f2ce3c861" name="Price" isLeaf="false" isStatic="false" isReadOnly="false" isUnique="false" isDerived="false" isDerivedUnion="false" aggregation="None" isComposite="false">
            <elementDefinition Id="bc425a52-3374-42dd-a7fc-23af5b71685c" />
            <type_NamedElement>
              <referencedTypeMoniker Id="b3009d99-3060-464b-91db-2d89eac4632b" LastKnownName="decimal" />
            </type_NamedElement>
          </property>
          <property Id="279c68a5-61bc-4397-8549-e57e8dcf0f03" name="Category" isLeaf="false" isStatic="false" isReadOnly="false" isUnique="false" isDerived="false" isDerivedUnion="false" aggregation="None" isComposite="false">
            <elementDefinition Id="35991e94-eedb-41cb-add4-b3e3573a8f6f" />
            <type_NamedElement>
              <referencedTypeMoniker Id="2a6dcd0a-0273-4010-921a-49f2fd199f54" LastKnownName="Category" />
            </type_NamedElement>
          </property>
          <property Id="2888fa1c-2050-4522-ab76-529d1aa87d22" name="Description" isLeaf="false" isStatic="false" isReadOnly="false" isUnique="false" isDerived="false" isDerivedUnion="false" aggregation="None" isComposite="false">
            <elementDefinition Id="4604a281-4a7b-4258-9b05-0f78bae61842" />
            <type_NamedElement>
              <referencedTypeMoniker Id="6a085a14-218c-4019-a67f-42d117c6917b" LastKnownName="String" />
            </type_NamedElement>
          </property>
          <property Id="bc72c7cc-4621-4788-a779-23c1e6409289" name="DelTime" isLeaf="false" isStatic="false" isReadOnly="false" isUnique="false" isDerived="false" isDerivedUnion="false" aggregation="None" isComposite="false">
            <elementDefinition Id="d2e7824f-3679-44a5-9cd2-d6ea87ed7a8c" />
            <type_NamedElement>
              <referencedTypeMoniker Id="5e95a766-896f-41c7-8951-778ddf708d7a" LastKnownName="DateTime" />
            </type_NamedElement>
          </property>
          <property Id="67d8e937-8e94-4b9b-8abf-154afa6a71c6" name="AvgServiceTime" isLeaf="false" isStatic="false" isReadOnly="false" isUnique="false" isDerived="false" isDerivedUnion="false" aggregation="None" isComposite="false">
            <elementDefinition Id="e928879f-8356-4415-92ef-f33c2cac90a3" />
            <type_NamedElement>
              <referencedTypeMoniker Id="afc7744e-e803-437f-814c-175324a339fb" LastKnownName="TimeSpan" />
            </type_NamedElement>
          </property>
        </ownedAttributesInternal>
        <ownedOperationsInternal>
          <operation Id="1ba5405b-775f-4124-a2e2-bf0a0596cd36" name="Service" isLeaf="false" isStatic="false" isAbstract="false" concurrency="Sequential" isQuery="false">
            <elementDefinition Id="e19fcc6a-a78e-4579-93dd-fa5f6396fceb" />
            <ownedParameters>
              <operationHasOwnedParameters>
                <parameter Id="c5a82761-e123-4890-aaf6-999098cab5a9" direction="Return" isUnique="false">
                  <elementDefinition Id="9be21005-2b6a-4ad4-ad87-ab8b595a62c3" />
                  <type_NamedElement>
                    <referencedTypeMoniker Id="62e1c591-1fc8-4d49-889d-ba3d80faa959" LastKnownName="void" />
                  </type_NamedElement>
                </parameter>
              </operationHasOwnedParameters>
            </ownedParameters>
          </operation>
          <operation Id="2cbf321f-67e7-4ee2-9afc-ccb237dbfd44" name="AddService" isLeaf="false" isStatic="false" isAbstract="false" concurrency="Sequential" isQuery="false">
            <elementDefinition Id="7b14cea4-cc91-4642-8257-6ed2263f8050" />
            <ownedParameters>
              <operationHasOwnedParameters>
                <parameter Id="461347b9-1a1e-438e-ab5c-0557c22441a5" direction="Return" isUnique="false">
                  <elementDefinition Id="b09ee138-7d2d-4fad-81c2-f904b39bee0a" />
                  <type_NamedElement>
                    <referencedTypeMoniker Id="6a45fed8-1689-4fa9-8e39-f876365db554" LastKnownName="bool" />
                  </type_NamedElement>
                </parameter>
              </operationHasOwnedParameters>
            </ownedParameters>
          </operation>
          <operation Id="bd21ac8a-dd49-4a99-96cf-ee70e6c94467" name="DelService" isLeaf="false" isStatic="false" isAbstract="false" concurrency="Sequential" isQuery="false">
            <elementDefinition Id="493f8adb-44eb-4052-94aa-94a96c5ce026" />
            <ownedParameters>
              <operationHasOwnedParameters>
                <parameter Id="0310138d-0578-47ae-a4ca-a1040162e22c" direction="Return" isUnique="false">
                  <elementDefinition Id="f1328904-caea-4392-a8a6-6fb81fadcc0c" />
                  <type_NamedElement>
                    <referencedTypeMoniker Id="6a45fed8-1689-4fa9-8e39-f876365db554" LastKnownName="bool" />
                  </type_NamedElement>
                </parameter>
              </operationHasOwnedParameters>
            </ownedParameters>
          </operation>
          <operation Id="02843dad-0af9-4d55-9846-924a16e5a91a" name="EditService" isLeaf="false" isStatic="false" isAbstract="false" concurrency="Sequential" isQuery="false">
            <elementDefinition Id="3f9a94cb-3a13-4090-b79d-763af4e3f5a8" />
            <ownedParameters>
              <operationHasOwnedParameters>
                <parameter Id="8ffd89ab-3daa-49dd-852d-d8d434eb3e7a" direction="Return" isUnique="false">
                  <elementDefinition Id="4dc94d21-a639-45e3-a938-9f31fa4f9ba5" />
                  <type_NamedElement>
                    <referencedTypeMoniker Id="6a45fed8-1689-4fa9-8e39-f876365db554" LastKnownName="bool" />
                  </type_NamedElement>
                </parameter>
              </operationHasOwnedParameters>
            </ownedParameters>
          </operation>
          <operation Id="946ed46e-d043-4e11-8baa-3ce1e49d29c2" name="CountInOrders" isLeaf="false" isStatic="false" isAbstract="false" concurrency="Sequential" isQuery="false">
            <elementDefinition Id="0eee3466-919d-40d3-acc0-a903f247a95a" />
            <ownedParameters>
              <operationHasOwnedParameters>
                <parameter Id="389933fc-f51b-452c-8103-730b66d87f59" name="from" direction="In" isUnique="false">
                  <elementDefinition Id="62f7f608-42e0-47e8-9c5a-ea8d82942d75" />
                  <type_NamedElement>
                    <referencedTypeMoniker Id="692b2aee-bd60-4b53-a628-86edf58087d0" LastKnownName="Datetime" />
                  </type_NamedElement>
                </parameter>
              </operationHasOwnedParameters>
              <operationHasOwnedParameters>
                <parameter Id="cf17b0c1-56a7-48ed-88bc-f7b0af93692f" name="until" direction="In" isUnique="false">
                  <elementDefinition Id="10169865-3f9f-4090-8d9e-2ca4f06ea214" />
                  <type_NamedElement>
                    <referencedTypeMoniker Id="5e95a766-896f-41c7-8951-778ddf708d7a" LastKnownName="DateTime" />
                  </type_NamedElement>
                </parameter>
              </operationHasOwnedParameters>
              <operationHasOwnedParameters>
                <parameter Id="a33dd4c2-e099-425b-8551-f95ebf16ed48" direction="Return" isUnique="false">
                  <elementDefinition Id="63963da1-88a7-481a-a45b-68a7b698bb18" />
                  <type_NamedElement>
                    <referencedTypeMoniker Id="de578a74-cb65-4d29-833c-4c0b903c29db" LastKnownName="int" />
                  </type_NamedElement>
                </parameter>
              </operationHasOwnedParameters>
            </ownedParameters>
          </operation>
        </ownedOperationsInternal>
      </class>
    </logicalClassDesignerModelHasTypes>
    <packageHasNamedElement>
      <referencedType Id="056c53aa-cdd8-46ea-98df-0259d1a4b020" name="String" isAbstract="false" isLeaf="false" cachedFullName="String">
        <elementDefinition Id="59259974-6d55-42c6-b7bd-763d77ac8ef9" />
      </referencedType>
    </packageHasNamedElement>
    <packageHasNamedElement>
      <referencedType Id="f0f44efc-4066-4ed3-9ddd-5070b9ce1adb" name="Integer" isAbstract="false" isLeaf="false" cachedFullName="Integer">
        <elementDefinition Id="220a3521-e091-4221-bae9-3ef9018e845c" />
      </referencedType>
    </packageHasNamedElement>
    <packageHasNamedElement>
      <referencedType Id="6a085a14-218c-4019-a67f-42d117c6917b" name="String" isAbstract="false" isLeaf="false" cachedFullName="String">
        <elementDefinition Id="59259974-6d55-42c6-b7bd-763d77ac8ef9" />
      </referencedType>
    </packageHasNamedElement>
    <logicalClassDesignerModelHasTypes>
      <class Id="04d085bd-93e1-404d-b8cd-d5e6b85bd1ed" name="Order" isAbstract="false" isLeaf="false" isActiveClass="false">
        <elementDefinition Id="4256f795-28db-49f0-8022-8f48d9c63bbe" />
        <targetEnds>
          <association Id="36ca54d4-0b06-4b5f-add0-19f71aca0baf" isDerived="false" sourceEndRoleName="Order" targetEndRoleName="Master" isLeaf="false" isAbstract="false">
            <classMoniker Id="f87435e5-83d1-45e9-8965-813f6d8a5e7d" LastKnownName="Master" />
            <relationshipOwnedElementsInternal>
              <associationHasOwnedEnds>
                <memberEnd Id="35c48265-24d3-4698-be44-c740bca80767" name="Order" isLeaf="false" isStatic="false" isReadOnly="false" isDerived="false" isDerivedUnion="false" aggregation="Composite" isComposite="false" isNavigableOwned="false">
                  <lowerValueInternal>
                    <literalString Id="87348d4c-d86c-434a-9908-47197d5dcb8f" name="Lower" value="0">
                      <elementDefinition Id="8faed958-3b6f-49a6-86bd-eda814ff696f" />
                    </literalString>
                  </lowerValueInternal>
                  <upperValueInternal>
                    <literalString Id="b7a1a466-a529-4a7a-9aba-3c404eeb7d2f" name="Upper" value="*">
                      <elementDefinition Id="781cccb5-7625-472c-a766-2e094275ce69" />
                    </literalString>
                  </upperValueInternal>
                  <elementDefinition Id="fe87ad70-5007-4647-8304-29ce28342cc4" />
                </memberEnd>
              </associationHasOwnedEnds>
              <associationHasOwnedEnds>
                <memberEnd Id="40452cea-f470-47d7-b698-06243615b514" name="Master" isLeaf="false" isStatic="false" isReadOnly="false" isDerived="false" isDerivedUnion="false" aggregation="None" isComposite="true">
                  <elementDefinition Id="66cf772c-cc79-4e5d-b714-315ba4e2a4c3" />
                </memberEnd>
              </associationHasOwnedEnds>
            </relationshipOwnedElementsInternal>
            <elementDefinition Id="804c733e-a2a7-4a6a-a1f8-6081119b9f65" />
          </association>
          <association Id="54c4f532-bcd5-4f73-b5e7-9aac0ed78679" isDerived="false" sourceEndRoleName="Order" targetEndRoleName="Manager" isLeaf="false" isAbstract="false">
            <classMoniker Id="b6856be0-2a50-4617-a0c0-c385060eb4f9" LastKnownName="Manager" />
            <relationshipOwnedElementsInternal>
              <associationHasOwnedEnds>
                <memberEnd Id="1b5085d9-4baf-4a7e-9ab9-e6d26ef7f20d" name="Order" isLeaf="false" isStatic="false" isReadOnly="false" isDerived="false" isDerivedUnion="false" aggregation="Composite" isComposite="false" isNavigableOwned="false">
                  <lowerValueInternal>
                    <literalString Id="0a6741af-074a-4566-9df5-052988235900" name="Lower" value="0">
                      <elementDefinition Id="a271b047-8920-47e8-8d7a-4baf4c2f4547" />
                    </literalString>
                  </lowerValueInternal>
                  <upperValueInternal>
                    <literalString Id="2405cc60-d9c8-4edd-8737-b1a95a99b0cb" name="Upper" value="*">
                      <elementDefinition Id="6f3527cc-3e20-4c99-9e77-58cd58b8310e" />
                    </literalString>
                  </upperValueInternal>
                  <elementDefinition Id="c5a7cc1e-4325-4d9c-941d-82d545e012d0" />
                </memberEnd>
              </associationHasOwnedEnds>
              <associationHasOwnedEnds>
                <memberEnd Id="19138d61-0f7c-4d87-853f-bd311c81a3e3" name="Manager" isLeaf="false" isStatic="false" isReadOnly="false" isDerived="false" isDerivedUnion="false" aggregation="None" isComposite="true">
                  <elementDefinition Id="41a69f9c-d719-4c5b-b040-6f6431f5630d" />
                </memberEnd>
              </associationHasOwnedEnds>
            </relationshipOwnedElementsInternal>
            <elementDefinition Id="f47b2794-f065-4eb9-9e78-96b42e98510c" />
          </association>
          <association Id="bff8334f-2709-42be-bcb5-545a1593e11a" isDerived="false" sourceEndRoleName="Order " targetEndRoleName="Workshop" isLeaf="false" isAbstract="false">
            <classMoniker Id="cd276153-9c6d-4ebc-b0d1-a6e2838d7c37" LastKnownName="Workshop" />
            <relationshipOwnedElementsInternal>
              <associationHasOwnedEnds>
                <memberEnd Id="deb24abb-72c6-4b8a-a2ba-fd43d6f34bd7" name="Order " isLeaf="false" isStatic="false" isReadOnly="false" isDerived="false" isDerivedUnion="false" aggregation="Composite" isComposite="false" isNavigableOwned="false">
                  <lowerValueInternal>
                    <literalString Id="c8f1f9f0-8ee6-4047-9172-e96a3d1a269a" name="Lower" value="0">
                      <elementDefinition Id="92101b92-58fc-4184-9f51-f1ba177feb49" />
                    </literalString>
                  </lowerValueInternal>
                  <upperValueInternal>
                    <literalString Id="e92baac1-e25d-4979-b7f4-b342f3f88e15" name="Upper" value="*">
                      <elementDefinition Id="3ae9d686-7afc-4a22-9d2d-b70fd66b58c5" />
                    </literalString>
                  </upperValueInternal>
                  <elementDefinition Id="4c7abcbd-4f27-4de3-8aca-1168a093bd69" />
                </memberEnd>
              </associationHasOwnedEnds>
              <associationHasOwnedEnds>
                <memberEnd Id="4a757c95-702a-41f5-b475-35756db92f8d" name="Workshop" isLeaf="false" isStatic="false" isReadOnly="false" isDerived="false" isDerivedUnion="false" aggregation="None" isComposite="true">
                  <elementDefinition Id="88c24fa7-1ff6-4f49-a65b-b90fb46c75de" />
                </memberEnd>
              </associationHasOwnedEnds>
            </relationshipOwnedElementsInternal>
            <elementDefinition Id="f22866e0-0c86-4556-a22a-7b4f9433ab8c" />
          </association>
          <association Id="fb934181-fc93-4010-ac03-1382661e88bd" isDerived="false" sourceEndRoleName="Order" targetEndRoleName="OrderLog" isLeaf="false" isAbstract="false">
            <classMoniker Id="615b5a0b-9df7-4ecc-9d4d-9b4ff89160e5" LastKnownName="OrderLog" />
            <relationshipOwnedElementsInternal>
              <associationHasOwnedEnds>
                <memberEnd Id="a89f53b9-2c2d-4df0-ac6c-50b496e84c17" name="Order" isLeaf="false" isStatic="false" isReadOnly="false" isDerived="false" isDerivedUnion="false" aggregation="Composite" isComposite="false" isNavigableOwned="false">
                  <elementDefinition Id="f7545e35-a072-4af2-8aeb-a764abc55649" />
                </memberEnd>
              </associationHasOwnedEnds>
              <associationHasOwnedEnds>
                <memberEnd Id="ebd53ff6-d6b8-48c8-8fe0-7e5a5ad69c0d" name="OrderLog" isLeaf="false" isStatic="false" isReadOnly="false" isDerived="false" isDerivedUnion="false" aggregation="None" isComposite="true">
                  <lowerValueInternal>
                    <literalString Id="353bab18-9582-4b38-9d66-7cd12bf105d9" name="Lower" value="0">
                      <elementDefinition Id="4853f564-0b08-4f39-974e-f287c2a65498" />
                    </literalString>
                  </lowerValueInternal>
                  <upperValueInternal>
                    <literalString Id="7676ec68-fe17-4447-96fe-45ac56dadb3a" name="Upper" value="*">
                      <elementDefinition Id="15229eef-6c3d-4cd9-9eac-24b07a13663a" />
                    </literalString>
                  </upperValueInternal>
                  <elementDefinition Id="4f886dc4-4722-4336-a8bc-ecb7b4461f6c" />
                </memberEnd>
              </associationHasOwnedEnds>
            </relationshipOwnedElementsInternal>
            <elementDefinition Id="e4f84773-549d-46bf-81f3-322a028c5934" />
          </association>
          <association Id="56994a21-5baf-4dfd-801f-0b89c87f703f" isDerived="false" sourceEndRoleName="Order" targetEndRoleName="OrderServices" isLeaf="false" isAbstract="false">
            <classMoniker Id="f44e71d1-104b-44ed-86a0-4e29fb8f812c" LastKnownName="OrderService" />
            <relationshipOwnedElementsInternal>
              <associationHasOwnedEnds>
                <memberEnd Id="6e671f43-91d6-444d-a33a-fe0c7737c327" name="Order" isLeaf="false" isStatic="false" isReadOnly="false" isDerived="false" isDerivedUnion="false" aggregation="Composite" isComposite="false" isNavigableOwned="false">
                  <lowerValueInternal>
                    <literalString Id="cfa5c1e7-7034-4f44-b141-d0ca56f4c9a0" name="Lower" value="0">
                      <elementDefinition Id="8b32299d-efdb-43d7-a564-dace167557b4" />
                    </literalString>
                  </lowerValueInternal>
                  <upperValueInternal>
                    <literalString Id="7b56c9f5-198f-446f-b850-b4197d30fab7" name="Upper" value="1">
                      <elementDefinition Id="2f6aaa44-e525-42be-8aa0-646225746cad" />
                    </literalString>
                  </upperValueInternal>
                  <elementDefinition Id="ac3d9773-1713-4bae-96b8-0e20acbedb23" />
                </memberEnd>
              </associationHasOwnedEnds>
              <associationHasOwnedEnds>
                <memberEnd Id="154b930a-7003-4b99-a43b-90376dce6b1c" name="OrderServices" isLeaf="false" isStatic="false" isReadOnly="false" isDerived="false" isDerivedUnion="false" aggregation="None" isComposite="true">
                  <lowerValueInternal>
                    <literalString Id="ed2e0903-972d-4ae7-a5ea-42e883440bac" name="Lower" value="1">
                      <elementDefinition Id="dfe371d5-2d09-4ff2-bdf9-3252a09c48e9" />
                    </literalString>
                  </lowerValueInternal>
                  <upperValueInternal>
                    <literalString Id="4092d0e2-149f-4265-9eff-a728edfbe690" name="Upper" value="*">
                      <elementDefinition Id="b6d201db-3f3d-4104-b180-8ff0f40f84de" />
                    </literalString>
                  </upperValueInternal>
                  <elementDefinition Id="844b5d67-df0c-4fef-9b3d-1ce251ddd26c" />
                </memberEnd>
              </associationHasOwnedEnds>
            </relationshipOwnedElementsInternal>
            <elementDefinition Id="500588e1-5910-4fe0-84c4-1d1f1c15cd42" />
          </association>
          <association Id="01be2a42-9c6b-406a-8da1-8eb2f75c0db6" isDerived="false" sourceEndRoleName="Order" targetEndRoleName="Product" isLeaf="false" isAbstract="false">
            <classMoniker Id="9b4b7581-ed32-482e-b87e-80fb21168b7b" LastKnownName="Product" />
            <relationshipOwnedElementsInternal>
              <associationHasOwnedEnds>
                <memberEnd Id="991a2709-059b-4087-b71f-34d366f04309" name="Order" isLeaf="false" isStatic="false" isReadOnly="false" isDerived="false" isDerivedUnion="false" aggregation="Composite" isComposite="false" isNavigableOwned="false">
                  <lowerValueInternal>
                    <literalString Id="2c3d95e6-62cf-490c-9758-c6bd45e98cab" name="Lower" value="1">
                      <elementDefinition Id="32bfd94f-00f8-4f00-a7e6-59f5b5276317" />
                    </literalString>
                  </lowerValueInternal>
                  <upperValueInternal>
                    <literalString Id="21539b39-9309-4060-b83c-62fb33107cd9" name="Upper" value="*">
                      <elementDefinition Id="9c7bb56f-4419-40a2-9ace-dd34361a86e8" />
                    </literalString>
                  </upperValueInternal>
                  <elementDefinition Id="3cb33913-926d-41d3-ba59-326a86b12968" />
                </memberEnd>
              </associationHasOwnedEnds>
              <associationHasOwnedEnds>
                <memberEnd Id="e49c1423-b6f3-4d8f-bf52-0324d9721d36" name="Product" isLeaf="false" isStatic="false" isReadOnly="false" isDerived="false" isDerivedUnion="false" aggregation="None" isComposite="true">
                  <elementDefinition Id="ea423272-3473-4dcc-b853-c75743c18a60" />
                </memberEnd>
              </associationHasOwnedEnds>
            </relationshipOwnedElementsInternal>
            <elementDefinition Id="d2b54529-e606-45e4-a323-ff7ee7698003" />
          </association>
        </targetEnds>
        <ownedAttributesInternal>
          <property Id="40edd035-2f1c-4610-9369-1e36f0daebe1" name="id" isLeaf="false" isStatic="false" isReadOnly="false" isUnique="false" isDerived="false" isDerivedUnion="false" aggregation="None" isComposite="false">
            <elementDefinition Id="48112cbf-70ac-40eb-b3f3-648d2acaf044" />
            <type_NamedElement>
              <referencedTypeMoniker Id="0082579e-04fe-43f7-a6b8-d2994e95b3d6" LastKnownName="Integer" />
            </type_NamedElement>
          </property>
          <property Id="afa74f6a-1252-4704-a4b0-f7bb69834471" name="Product" isLeaf="false" isStatic="false" isReadOnly="false" isUnique="false" isDerived="false" isDerivedUnion="false" aggregation="None" isComposite="false">
            <elementDefinition Id="1239f398-e522-4268-b303-2c0684f020c5" />
            <type_NamedElement>
              <referencedTypeMoniker Id="603e91ec-7198-40f7-a47d-8e53c0e49d75" LastKnownName="Product" />
            </type_NamedElement>
          </property>
          <property Id="6b612539-9176-4666-8ec7-152bc287fb07" name="Master" isLeaf="false" isStatic="false" isReadOnly="false" isUnique="false" isDerived="false" isDerivedUnion="false" aggregation="None" isComposite="false">
            <elementDefinition Id="c4064fed-ba35-4fcc-9872-2ab08c3b62b4" />
            <type_NamedElement>
              <referencedTypeMoniker Id="4c13560b-accc-4537-a466-aff55cd8e227" LastKnownName="Master" />
            </type_NamedElement>
          </property>
          <property Id="d3fa0c1a-7b3e-4cde-b0f7-588946ab0525" name="DateStart" isLeaf="false" isStatic="false" isReadOnly="false" isUnique="false" isDerived="false" isDerivedUnion="false" aggregation="None" isComposite="false">
            <elementDefinition Id="1ba8cd69-db68-42b2-b541-2edd1387a828" />
            <type_NamedElement>
              <referencedTypeMoniker Id="6b3c41e0-5105-475b-a60d-2186a484e61d" LastKnownName="DateTime" />
            </type_NamedElement>
          </property>
          <property Id="ea7e29d2-9da4-48c3-99fb-0b482f417fc5" name="Status" isLeaf="false" isStatic="false" isReadOnly="false" isUnique="false" isDerived="false" isDerivedUnion="false" aggregation="None" isComposite="false">
            <elementDefinition Id="be396699-1533-4b66-a765-56234c000c9c" />
            <type_NamedElement>
              <referencedTypeMoniker Id="7bfa11b8-8bde-4368-8759-fc671404c53c" LastKnownName="OrderStatus" />
            </type_NamedElement>
          </property>
          <property Id="ef5d8305-40a8-4039-b4b1-98d9fd5b3fe8" name="Manager" isLeaf="false" isStatic="false" isReadOnly="false" isUnique="false" isDerived="false" isDerivedUnion="false" aggregation="None" isComposite="false">
            <elementDefinition Id="822e2f9f-0147-42b9-bd13-118eb505773f" />
            <type_NamedElement>
              <referencedTypeMoniker Id="25fea15f-c0c7-47ea-b7b4-c6007a2f6e20" LastKnownName="Manager" />
            </type_NamedElement>
          </property>
          <property Id="bfd56c0a-e55f-42d9-9ee8-d4579c4d4ee4" name="ClientComment" isLeaf="false" isStatic="false" isReadOnly="false" isUnique="false" isDerived="false" isDerivedUnion="false" aggregation="None" isComposite="false">
            <elementDefinition Id="6decc870-2861-41b4-bd71-87b43feada7b" />
            <type_NamedElement>
              <referencedTypeMoniker Id="0dd4815a-6dbc-41c7-b719-9622cbfbbb8f" LastKnownName="String" />
            </type_NamedElement>
          </property>
          <property Id="470042cb-5544-4822-9ac0-52b9ae9d0bd6" name="DateDiagnostic" isLeaf="false" isStatic="false" isReadOnly="false" isUnique="false" isDerived="false" isDerivedUnion="false" aggregation="None" isComposite="false">
            <elementDefinition Id="c015f39c-ee2e-4e73-bdc2-132d36c96344" />
            <type_NamedElement>
              <referencedTypeMoniker Id="f74590fe-7b39-49d1-9aa0-7d9209443024" LastKnownName="DateTime" />
            </type_NamedElement>
          </property>
          <property Id="d60b941a-a7fb-439c-afe3-b4ae15cddef1" name="DateFinish" isLeaf="false" isStatic="false" isReadOnly="false" isUnique="false" isDerived="false" isDerivedUnion="false" aggregation="None" isComposite="false">
            <elementDefinition Id="a24c8cc6-b08c-4951-9059-e78c59f2a7bb" />
            <type_NamedElement>
              <referencedTypeMoniker Id="a50b5088-35ce-4516-9bba-64711c467f82" LastKnownName="DateTime" />
            </type_NamedElement>
          </property>
          <property Id="20189353-b63d-41cd-8a50-0409c46c63b8" name="DateClientAnswer" isLeaf="false" isStatic="false" isReadOnly="false" isUnique="false" isDerived="false" isDerivedUnion="false" aggregation="None" isComposite="false">
            <elementDefinition Id="136d3f3b-285d-45bc-a44d-7429439d935d" />
            <type_NamedElement>
              <referencedTypeMoniker Id="5e95a766-896f-41c7-8951-778ddf708d7a" LastKnownName="DateTime" />
            </type_NamedElement>
          </property>
          <property Id="30f92922-e354-488c-b05e-5ec33a91cdab" name="DatePaid" isLeaf="false" isStatic="false" isReadOnly="false" isUnique="false" isDerived="false" isDerivedUnion="false" aggregation="None" isComposite="false">
            <elementDefinition Id="59f3832b-08d1-4d65-b2a0-24d60b10a414" />
            <type_NamedElement>
              <referencedTypeMoniker Id="5e95a766-896f-41c7-8951-778ddf708d7a" LastKnownName="DateTime" />
            </type_NamedElement>
          </property>
          <property Id="31d614c1-5b65-4f69-869c-524b43897386" name="DateCancel" isLeaf="false" isStatic="false" isReadOnly="false" isUnique="false" isDerived="false" isDerivedUnion="false" aggregation="None" isComposite="false">
            <elementDefinition Id="bd25baaa-196d-44d9-bb3b-02f53f87de6e" />
            <type_NamedElement>
              <referencedTypeMoniker Id="5e95a766-896f-41c7-8951-778ddf708d7a" LastKnownName="DateTime" />
            </type_NamedElement>
          </property>
          <property Id="e07c651d-5e46-4075-b469-38d7bb57dd43" name="DateRepaired" isLeaf="false" isStatic="false" isReadOnly="false" isUnique="false" isDerived="false" isDerivedUnion="false" aggregation="None" isComposite="false">
            <elementDefinition Id="99769142-1977-4d13-95ba-c03510426976" />
            <type_NamedElement>
              <referencedTypeMoniker Id="5e95a766-896f-41c7-8951-778ddf708d7a" LastKnownName="DateTime" />
            </type_NamedElement>
          </property>
          <property Id="f1eb9a6b-d9b7-44e0-8c12-ddddb503bf96" name="Workshop" isLeaf="false" isStatic="false" isReadOnly="false" isUnique="false" isDerived="false" isDerivedUnion="false" aggregation="None" isComposite="false">
            <elementDefinition Id="8a1980c9-3b91-4dbd-a27a-0facfef880e5" />
            <type_NamedElement>
              <referencedTypeMoniker Id="f4c65483-48fa-48c6-b1ba-774306746da9" LastKnownName="Workshop" />
            </type_NamedElement>
          </property>
          <property Id="3ac5fbb5-23c0-4964-ad84-e7367d81698b" name="FinalPrice" isLeaf="false" isStatic="false" isReadOnly="false" isUnique="false" isDerived="false" isDerivedUnion="false" aggregation="None" isComposite="false">
            <elementDefinition Id="8f12b31f-e1a8-4455-9d0a-24d5b86578e2" />
            <type_NamedElement>
              <referencedTypeMoniker Id="96e8787e-95db-4d57-93e2-e6a85b70e26b" LastKnownName="decimal" />
            </type_NamedElement>
          </property>
          <property Id="06bf2b23-eb44-4c2f-8275-8e7c313e9dbc" name="DatePreapayment" isLeaf="false" isStatic="false" isReadOnly="false" isUnique="false" isDerived="false" isDerivedUnion="false" aggregation="None" isComposite="false">
            <elementDefinition Id="5deecaad-a59e-4c84-b55b-b7e4de5ddb7f" />
            <type_NamedElement>
              <referencedTypeMoniker Id="5e95a766-896f-41c7-8951-778ddf708d7a" LastKnownName="DateTime" />
            </type_NamedElement>
          </property>
          <property Id="c946b063-6f82-4b1f-87a6-9eebdf28a90c" name="ClientSale" isLeaf="false" isStatic="false" isReadOnly="false" isUnique="false" isDerived="false" isDerivedUnion="false" aggregation="None" isComposite="false">
            <elementDefinition Id="fff6d6aa-63d2-435d-8917-e7ec138e5b3d" />
            <type_NamedElement>
              <referencedTypeMoniker Id="d27a172f-da7d-4650-83eb-7613dcbd12a0" LastKnownName="decimal" />
            </type_NamedElement>
          </property>
          <property Id="5d80576a-27bd-40e5-bdb0-1344c3fc19b6" name="PrepaymentRequired" isLeaf="false" isStatic="false" isReadOnly="false" isUnique="false" isDerived="false" isDerivedUnion="false" aggregation="None" isComposite="false">
            <elementDefinition Id="266e5710-d5b5-40ba-9958-0297522f8fac" />
            <type_NamedElement>
              <referencedTypeMoniker Id="492a3225-13c7-450a-9a5d-6a3e9d6f38b5" LastKnownName="decimal" />
            </type_NamedElement>
          </property>
          <property Id="01899743-6c57-4c90-b5da-1cfdfd80de41" name="DateRefund" isLeaf="false" isStatic="false" isReadOnly="false" isUnique="false" isDerived="false" isDerivedUnion="false" aggregation="None" isComposite="false">
            <elementDefinition Id="72a6b948-e427-49b2-b1b3-154d554fa2a7" />
            <type_NamedElement>
              <referencedTypeMoniker Id="9ba371f3-5764-432a-b0fa-254535119fbd" LastKnownName="DeteTime" />
            </type_NamedElement>
          </property>
          <property Id="ae37f586-7796-4c9c-abce-fe7fea1b32f1" name="PrepaymentMade" isLeaf="false" isStatic="false" isReadOnly="false" isUnique="false" isDerived="false" isDerivedUnion="false" aggregation="None" isComposite="false">
            <elementDefinition Id="9a90ccb2-0ce9-43bf-8866-ac03b0085efc" />
            <type_NamedElement>
              <referencedTypeMoniker Id="d0e2218a-5be7-46cf-97a2-091e3a6a80e0" LastKnownName="decimal" />
            </type_NamedElement>
          </property>
        </ownedAttributesInternal>
        <ownedOperationsInternal>
          <operation Id="bcaafacf-e70d-458a-aa8e-56fcad3b2803" name="CalcFinalPrice" isLeaf="false" isStatic="false" isAbstract="false" concurrency="Sequential" isQuery="false">
            <elementDefinition Id="eb4c384f-b865-4575-9e1d-db9db5c1a18f" />
            <ownedParameters>
              <operationHasOwnedParameters>
                <parameter Id="057df51a-9ba6-4f88-b247-e716001770f5" direction="Return" isUnique="false">
                  <elementDefinition Id="496f4d9d-f17f-48ba-a55b-33bb8c8faa8f" />
                  <type_NamedElement>
                    <referencedTypeMoniker Id="d0e2218a-5be7-46cf-97a2-091e3a6a80e0" LastKnownName="decimal" />
                  </type_NamedElement>
                </parameter>
              </operationHasOwnedParameters>
            </ownedParameters>
          </operation>
          <operation Id="ebe79685-b997-47b0-87bd-dfc3997413fa" name="GetServices" isLeaf="false" isStatic="false" isAbstract="false" concurrency="Sequential" isQuery="false">
            <elementDefinition Id="86be7a71-d13f-4c08-9818-0c8787a43ee6" />
            <ownedParameters>
              <operationHasOwnedParameters>
                <parameter Id="90c532e0-0518-4af8-95fa-1f1e8434d582" direction="Return" isUnique="false">
                  <elementDefinition Id="aa804b9d-6990-4450-ba75-028c581d8f67" />
                  <type_NamedElement>
                    <referencedTypeMoniker Id="cef214f0-1a08-4369-af4b-81010021238c" LastKnownName="List&lt;OrderServices&gt;" />
                  </type_NamedElement>
                </parameter>
              </operationHasOwnedParameters>
              <operationHasOwnedParameters>
                <parameter Id="631e4dc4-444f-498b-be6b-c299ca3946fc" name="onlyUnfinished" direction="In" isUnique="false">
                  <elementDefinition Id="7c3ae05e-ba54-48cc-963e-ca549337c124" />
                  <type_NamedElement>
                    <referencedTypeMoniker Id="6a45fed8-1689-4fa9-8e39-f876365db554" LastKnownName="bool" />
                  </type_NamedElement>
                </parameter>
              </operationHasOwnedParameters>
            </ownedParameters>
          </operation>
          <operation Id="c6042c9e-70e2-40b2-a609-642655594e96" name="GetSpareParts" isLeaf="false" isStatic="false" isAbstract="false" concurrency="Sequential" isQuery="false">
            <elementDefinition Id="899fd99a-fc14-4976-ba5d-6f5225031d81" />
            <ownedParameters>
              <operationHasOwnedParameters>
                <parameter Id="167d16a4-2bf9-4e70-bbd6-c25ebcf52379" direction="Return" isUnique="false">
                  <elementDefinition Id="a3b1bb6b-b833-4bc0-8beb-2081b7e93e46" />
                  <type_NamedElement>
                    <referencedTypeMoniker Id="d2569f2f-9059-40dc-90e8-41a6ea4616c4" LastKnownName="List&lt;OrderSpareParts&gt;" />
                  </type_NamedElement>
                </parameter>
              </operationHasOwnedParameters>
            </ownedParameters>
          </operation>
          <operation Id="bb2a1666-7ac8-4d33-8e7f-14d1139e8ad1" name="GetOrderLogs" isLeaf="false" isStatic="false" isAbstract="false" concurrency="Sequential" isQuery="false">
            <elementDefinition Id="9239b69d-9f29-47f4-8755-13ac8a0cd97f" />
            <ownedParameters>
              <operationHasOwnedParameters>
                <parameter Id="91c87e80-d516-48a2-bade-23c6d3b64080" direction="Return" isUnique="false">
                  <elementDefinition Id="bd8d115d-1e96-44fd-a135-19d2ea7ef0d9" />
                  <type_NamedElement>
                    <referencedTypeMoniker Id="61e08e1c-740f-48fe-bf55-4101ae916fa8" LastKnownName="List&lt;OrderLog&gt;" />
                  </type_NamedElement>
                </parameter>
              </operationHasOwnedParameters>
            </ownedParameters>
          </operation>
          <operation Id="a8868280-f41a-4a07-98e3-da29af409554" name="CheckPartsDelivered" isLeaf="false" isStatic="false" isAbstract="false" concurrency="Sequential" isQuery="false">
            <elementDefinition Id="ee121927-bede-4d4a-a29f-d980cff15f9c" />
            <ownedParameters>
              <operationHasOwnedParameters>
                <parameter Id="ad8968a6-b5cf-4ce3-894d-9ab404be2f08" direction="Return" isUnique="false">
                  <elementDefinition Id="8c22a198-2c67-4189-a143-4c07d15e77cd" />
                  <type_NamedElement>
                    <referencedTypeMoniker Id="6a45fed8-1689-4fa9-8e39-f876365db554" LastKnownName="bool" />
                  </type_NamedElement>
                </parameter>
              </operationHasOwnedParameters>
            </ownedParameters>
          </operation>
          <operation Id="a83872ca-bd3d-4021-b31e-2a38122e39e7" name="CalcPrepayment" isLeaf="false" isStatic="false" isAbstract="false" concurrency="Sequential" isQuery="false">
            <elementDefinition Id="0a4ea2a0-b906-4f72-abfe-7534ad92f151" />
            <ownedParameters>
              <operationHasOwnedParameters>
                <parameter Id="3ff98b93-9a35-4f08-9828-f7edbeb935d8" direction="Return" isUnique="false">
                  <elementDefinition Id="4de82834-35a6-42ac-b860-0aebbcea1709" />
                  <type_NamedElement>
                    <referencedTypeMoniker Id="d0e2218a-5be7-46cf-97a2-091e3a6a80e0" LastKnownName="decimal" />
                  </type_NamedElement>
                </parameter>
              </operationHasOwnedParameters>
            </ownedParameters>
          </operation>
          <operation Id="a486cca0-72a7-43ab-aabc-b1dd522cbdaa" name="AddOrder" isLeaf="false" isStatic="false" isAbstract="false" concurrency="Sequential" isQuery="false">
            <elementDefinition Id="9514c05d-7688-448c-bfd8-d1584e294bde" />
            <ownedParameters>
              <operationHasOwnedParameters>
                <parameter Id="845a0560-202f-4b9c-b8b5-5d6ceed8b734" direction="Return" isUnique="false">
                  <elementDefinition Id="2df80490-93e0-4914-8ee0-e72628b8be0f" />
                  <type_NamedElement>
                    <referencedTypeMoniker Id="6a45fed8-1689-4fa9-8e39-f876365db554" LastKnownName="bool" />
                  </type_NamedElement>
                </parameter>
              </operationHasOwnedParameters>
            </ownedParameters>
          </operation>
          <operation Id="d72c30c0-12aa-4d6f-81ea-f86620f859f9" name="EditOrder" isLeaf="false" isStatic="false" isAbstract="false" concurrency="Sequential" isQuery="false">
            <elementDefinition Id="39eb1063-91b3-4b64-9c1f-743892c9e6b0" />
            <ownedParameters>
              <operationHasOwnedParameters>
                <parameter Id="82017892-e5e4-453f-8940-d951c1934aed" direction="Return" isUnique="false">
                  <elementDefinition Id="7a7e9b06-c7dc-4cf4-8a6e-69c7203145ce" />
                  <type_NamedElement>
                    <referencedTypeMoniker Id="6a45fed8-1689-4fa9-8e39-f876365db554" LastKnownName="bool" />
                  </type_NamedElement>
                </parameter>
              </operationHasOwnedParameters>
            </ownedParameters>
          </operation>
          <operation Id="0e75d05c-b2e5-4ecd-a809-bfe82a61a453" name="AddService" isLeaf="false" isStatic="false" isAbstract="false" concurrency="Sequential" isQuery="false">
            <elementDefinition Id="f0f76672-f6e7-46a1-a40e-d6a01e221727" />
            <ownedParameters>
              <operationHasOwnedParameters>
                <parameter Id="7f815923-8acc-4468-a433-4e3623f9a49f" name="service" direction="In" isUnique="false">
                  <elementDefinition Id="8225cbd9-cd7f-43b8-8808-c166f6742ae0" />
                  <type_NamedElement>
                    <referencedTypeMoniker Id="f2d6aefd-92fc-4df3-9170-5a77b35a77da" LastKnownName="OrderService" />
                  </type_NamedElement>
                </parameter>
              </operationHasOwnedParameters>
              <operationHasOwnedParameters>
                <parameter Id="39b77a2f-79c4-4177-a873-5dc450b85064" direction="Return" isUnique="false">
                  <elementDefinition Id="598305fa-363d-436b-887a-1f28c2798c3e" />
                  <type_NamedElement>
                    <referencedTypeMoniker Id="6a45fed8-1689-4fa9-8e39-f876365db554" LastKnownName="bool" />
                  </type_NamedElement>
                </parameter>
              </operationHasOwnedParameters>
            </ownedParameters>
          </operation>
          <operation Id="c2a9c1ce-7c8f-46e8-b94e-57091653efad" name="DelService" isLeaf="false" isStatic="false" isAbstract="false" concurrency="Sequential" isQuery="false">
            <elementDefinition Id="4ec16950-208e-46fa-911b-1716ddc7216e" />
            <ownedParameters>
              <operationHasOwnedParameters>
                <parameter Id="b67a59ca-c08a-4864-ab6a-504017838ab0" name="service" direction="In" isUnique="false">
                  <elementDefinition Id="c9333682-cc12-4e03-a22d-d4d9c0122e95" />
                  <type_NamedElement>
                    <referencedTypeMoniker Id="f2d6aefd-92fc-4df3-9170-5a77b35a77da" LastKnownName="OrderService" />
                  </type_NamedElement>
                </parameter>
              </operationHasOwnedParameters>
              <operationHasOwnedParameters>
                <parameter Id="92d63686-3fc5-459a-bb92-e015c346dee1" direction="Return" isUnique="false">
                  <elementDefinition Id="85faae0a-5b98-4c0a-a2a8-4fa3501c08c1" />
                  <type_NamedElement>
                    <referencedTypeMoniker Id="6a45fed8-1689-4fa9-8e39-f876365db554" LastKnownName="bool" />
                  </type_NamedElement>
                </parameter>
              </operationHasOwnedParameters>
            </ownedParameters>
          </operation>
          <operation Id="b872f386-31e3-4065-a9b3-3e4dc8815660" name="EditService" isLeaf="false" isStatic="false" isAbstract="false" concurrency="Sequential" isQuery="false">
            <elementDefinition Id="82656d19-8b0f-4484-b6b5-8172adc27b8f" />
            <ownedParameters>
              <operationHasOwnedParameters>
                <parameter Id="e525e4de-5629-4bcd-a8e6-325c925cd119" name="service" direction="In" isUnique="false">
                  <elementDefinition Id="bbffb5f7-6eff-4cd9-897d-c45edc88323b" />
                  <type_NamedElement>
                    <referencedTypeMoniker Id="f2d6aefd-92fc-4df3-9170-5a77b35a77da" LastKnownName="OrderService" />
                  </type_NamedElement>
                </parameter>
              </operationHasOwnedParameters>
              <operationHasOwnedParameters>
                <parameter Id="81bf4a92-43a2-4485-bcc0-e6de95c63852" direction="Return" isUnique="false">
                  <elementDefinition Id="5557145d-2f01-4fcc-a0b4-887fe44ca320" />
                  <type_NamedElement>
                    <referencedTypeMoniker Id="6a45fed8-1689-4fa9-8e39-f876365db554" LastKnownName="bool" />
                  </type_NamedElement>
                </parameter>
              </operationHasOwnedParameters>
            </ownedParameters>
          </operation>
          <operation Id="adfb33e6-47c0-45b0-93d0-44efd739431f" name="FindMaster" isLeaf="false" isStatic="false" isAbstract="false" concurrency="Sequential" isQuery="false">
            <elementDefinition Id="cdcf2316-7b61-426c-b5fc-cfb27b8aa989" />
            <ownedParameters>
              <operationHasOwnedParameters>
                <parameter Id="73d7d017-6f32-47d1-a940-a0a769ec2a5e" direction="Return" isUnique="false">
                  <elementDefinition Id="290ac30c-43b6-45f3-93b5-e2d80b00ac15" />
                  <type_NamedElement>
                    <referencedTypeMoniker Id="6a45fed8-1689-4fa9-8e39-f876365db554" LastKnownName="bool" />
                  </type_NamedElement>
                </parameter>
              </operationHasOwnedParameters>
            </ownedParameters>
          </operation>
          <operation Id="4dd83ce6-698b-42f3-bff5-560eba74c971" name="CalcServicesPrice" isLeaf="false" isStatic="false" isAbstract="false" concurrency="Sequential" isQuery="false">
            <elementDefinition Id="1543da64-9f87-481c-ba57-ff75348eb5d8" />
            <ownedParameters>
              <operationHasOwnedParameters>
                <parameter Id="cf8b84ba-ad9f-4bd9-a1e4-9d62266507b0" direction="Return" isUnique="false">
                  <elementDefinition Id="3b826ee4-0835-4142-adf9-a2bfcc768007" />
                  <type_NamedElement>
                    <referencedTypeMoniker Id="d0e2218a-5be7-46cf-97a2-091e3a6a80e0" LastKnownName="decimal" />
                  </type_NamedElement>
                </parameter>
              </operationHasOwnedParameters>
            </ownedParameters>
          </operation>
          <operation Id="16a2bade-66bf-4659-b67d-b42a4234c3f5" name="CalcSparePartsPrice" isLeaf="false" isStatic="false" isAbstract="false" concurrency="Sequential" isQuery="false">
            <elementDefinition Id="412e53c3-8968-44e6-ac13-e656cc464fd8" />
            <ownedParameters>
              <operationHasOwnedParameters>
                <parameter Id="100db260-4e64-4048-84a5-c047b258a827" direction="Return" isUnique="false">
                  <elementDefinition Id="4bce7d6d-0c4d-4f24-b4f5-17733d7067d4" />
                  <type_NamedElement>
                    <referencedTypeMoniker Id="d0e2218a-5be7-46cf-97a2-091e3a6a80e0" LastKnownName="decimal" />
                  </type_NamedElement>
                </parameter>
              </operationHasOwnedParameters>
            </ownedParameters>
          </operation>
          <operation Id="8f4e75f0-73d6-4721-b89b-c5e1db8a3b7a" name="CheckServicesDone" isLeaf="false" isStatic="false" isAbstract="false" concurrency="Sequential" isQuery="false">
            <elementDefinition Id="a4407ac4-00f7-4c02-9983-9b6bc8012a89" />
            <ownedParameters>
              <operationHasOwnedParameters>
                <parameter Id="1734ed73-bbbd-4cef-ace4-4bd385d2a8e5" direction="Return" isUnique="false">
                  <elementDefinition Id="de34d298-3b21-4e43-a92d-d35fb2a3806c" />
                  <type_NamedElement>
                    <referencedTypeMoniker Id="6a45fed8-1689-4fa9-8e39-f876365db554" LastKnownName="bool" />
                  </type_NamedElement>
                </parameter>
              </operationHasOwnedParameters>
            </ownedParameters>
          </operation>
          <operation Id="065edcdb-75f5-48db-9511-538f8d458ce7" name="GetService" isLeaf="false" isStatic="false" isAbstract="false" concurrency="Sequential" isQuery="false">
            <elementDefinition Id="07a6a184-f7e8-49a2-8901-aa9429c7424d" />
            <ownedParameters>
              <operationHasOwnedParameters>
                <parameter Id="97d28b78-f363-4a9f-96ea-1ef59e9c53e9" direction="Return" isUnique="false">
                  <elementDefinition Id="5e7b5a91-b326-41c2-9901-a6324e53bf75" />
                  <type_NamedElement>
                    <referencedTypeMoniker Id="f2d6aefd-92fc-4df3-9170-5a77b35a77da" LastKnownName="OrderService" />
                  </type_NamedElement>
                </parameter>
              </operationHasOwnedParameters>
              <operationHasOwnedParameters>
                <parameter Id="f3e9d8b7-b3a3-4b6d-ac28-7426d30ba91e" name="id" direction="In" isUnique="false">
                  <elementDefinition Id="08327bd3-4d27-45f5-b5f7-34c8a283d816" />
                  <type_NamedElement>
                    <referencedTypeMoniker Id="de578a74-cb65-4d29-833c-4c0b903c29db" LastKnownName="int" />
                  </type_NamedElement>
                </parameter>
              </operationHasOwnedParameters>
            </ownedParameters>
          </operation>
          <operation Id="fa35ca56-5cfd-4b2d-b99f-12e6f8340c77" name="GetSparePart" isLeaf="false" isStatic="false" isAbstract="false" concurrency="Sequential" isQuery="false">
            <elementDefinition Id="6287b06f-5bf7-4d2a-8a89-e42a57db5ec2" />
            <ownedParameters>
              <operationHasOwnedParameters>
                <parameter Id="8528aeb7-3029-40ed-859a-6f6fd027d997" name="id" direction="In" isUnique="false">
                  <elementDefinition Id="be33d6f8-5235-48c1-be3f-9b9676c1d39d" />
                  <type_NamedElement>
                    <referencedTypeMoniker Id="de578a74-cb65-4d29-833c-4c0b903c29db" LastKnownName="int" />
                  </type_NamedElement>
                </parameter>
              </operationHasOwnedParameters>
              <operationHasOwnedParameters>
                <parameter Id="a9de30aa-a987-44a0-8324-5800218296c8" direction="Return" isUnique="false">
                  <elementDefinition Id="e91f77e5-c552-4277-806b-1e41756793fe" />
                  <type_NamedElement>
                    <referencedTypeMoniker Id="f6b29dd0-39a0-4152-918d-8671f63fda18" LastKnownName="OrderSparePart" />
                  </type_NamedElement>
                </parameter>
              </operationHasOwnedParameters>
            </ownedParameters>
          </operation>
          <operation Id="581213d3-77c4-438c-9cb4-c15e9671e408" name="CalcServicesCount" isLeaf="false" isStatic="false" isAbstract="false" concurrency="Sequential" isQuery="false">
            <elementDefinition Id="959c7474-a3fb-45bf-86d2-353a4a2706cc" />
            <ownedParameters>
              <operationHasOwnedParameters>
                <parameter Id="a839c9b8-2c50-4f35-9c21-5dbc60a63af0" direction="Return" isUnique="false">
                  <elementDefinition Id="8b8d8671-4289-448e-8bf2-851406a73f8a" />
                  <type_NamedElement>
                    <referencedTypeMoniker Id="de578a74-cb65-4d29-833c-4c0b903c29db" LastKnownName="int" />
                  </type_NamedElement>
                </parameter>
              </operationHasOwnedParameters>
            </ownedParameters>
          </operation>
          <operation Id="3860dd02-4d06-45c6-8a58-c5c7a08f985b" name="CheckService" isLeaf="false" isStatic="false" isAbstract="false" concurrency="Sequential" isQuery="false">
            <elementDefinition Id="8c468e02-ec77-441f-a739-c31825313156" />
            <ownedParameters>
              <operationHasOwnedParameters>
                <parameter Id="de2e9469-c0e4-4dd0-9d95-1e98e9ecd951" name="service" direction="In" isUnique="false">
                  <elementDefinition Id="71e5180f-4a1b-4c8f-9b9f-614687526fb5" />
                  <type_NamedElement>
                    <referencedTypeMoniker Id="9366a8a0-2c9f-4aeb-81b2-7a52156b3689" LastKnownName="Service" />
                  </type_NamedElement>
                </parameter>
              </operationHasOwnedParameters>
              <operationHasOwnedParameters>
                <parameter Id="462ba0e6-e84d-4305-a0c2-cb05bf3ce711" direction="Return" isUnique="false">
                  <elementDefinition Id="8bef972b-5bd7-4fcc-9fac-f9434191217e" />
                  <type_NamedElement>
                    <referencedTypeMoniker Id="6a45fed8-1689-4fa9-8e39-f876365db554" LastKnownName="bool" />
                  </type_NamedElement>
                </parameter>
              </operationHasOwnedParameters>
            </ownedParameters>
          </operation>
          <operation Id="aa1da1b3-0733-4d96-929b-098c1a2abb05" name="CheckSparePart" isLeaf="false" isStatic="false" isAbstract="false" concurrency="Sequential" isQuery="false">
            <elementDefinition Id="1467a6b5-62b6-43f8-a933-6be99809a1ec" />
            <ownedParameters>
              <operationHasOwnedParameters>
                <parameter Id="7b0f967c-b55a-4ac7-a393-d8054cb54048" direction="Return" isUnique="false">
                  <elementDefinition Id="35eadb7f-b526-4a3a-8a76-247d464d926a" />
                  <type_NamedElement>
                    <referencedTypeMoniker Id="6a45fed8-1689-4fa9-8e39-f876365db554" LastKnownName="bool" />
                  </type_NamedElement>
                </parameter>
              </operationHasOwnedParameters>
              <operationHasOwnedParameters>
                <parameter Id="3c2e44e7-1467-4b2d-b8b5-015e587079cd" name="sparePart" direction="In" isUnique="false">
                  <elementDefinition Id="e35da8b3-e401-4680-8c0b-dc8811a44417" />
                  <type_NamedElement>
                    <referencedTypeMoniker Id="df8dd8bd-98b9-4b9d-a18e-fcdb3b31fa72" LastKnownName="SparePart" />
                  </type_NamedElement>
                </parameter>
              </operationHasOwnedParameters>
            </ownedParameters>
          </operation>
          <operation Id="d4f99847-1d39-4e1b-9864-027584d85aff" name="CalcSparePartsCount" isLeaf="false" isStatic="false" isAbstract="false" concurrency="Sequential" isQuery="false">
            <elementDefinition Id="9882e88a-af78-41d1-a4dc-f92d76e9b146" />
            <ownedParameters>
              <operationHasOwnedParameters>
                <parameter Id="2c3e627e-2961-4509-9d11-7b2f5cbbf7cd" direction="Return" isUnique="false">
                  <elementDefinition Id="b1993c8a-124a-4b86-bdca-2123104fbd31" />
                  <type_NamedElement>
                    <referencedTypeMoniker Id="de578a74-cb65-4d29-833c-4c0b903c29db" LastKnownName="int" />
                  </type_NamedElement>
                </parameter>
              </operationHasOwnedParameters>
            </ownedParameters>
          </operation>
          <operation Id="2c79ef66-a7ee-4b84-ae6c-d9eb49459193" name="CalcSparePartsPrice" isLeaf="false" isStatic="false" isAbstract="false" concurrency="Sequential" isQuery="false">
            <elementDefinition Id="ddc6f3b8-a5e3-4d0c-b470-9500a93be1dc" />
            <ownedParameters>
              <operationHasOwnedParameters>
                <parameter Id="96f8c35b-8a08-4cac-b2c2-d534928c3b35" direction="Return" isUnique="false">
                  <elementDefinition Id="5bba44f2-49c7-4ed2-ae4f-2780ee9717ed" />
                  <type_NamedElement>
                    <referencedTypeMoniker Id="d0e2218a-5be7-46cf-97a2-091e3a6a80e0" LastKnownName="decimal" />
                  </type_NamedElement>
                </parameter>
              </operationHasOwnedParameters>
            </ownedParameters>
          </operation>
          <operation Id="0ac9875f-95c3-412e-bd70-1715615b1561" name="CalcClientPrepayment" isLeaf="false" isStatic="false" isAbstract="false" concurrency="Sequential" isQuery="false">
            <elementDefinition Id="7fd0bdf3-1084-43e3-86ed-c9f19c238b5e" />
            <ownedParameters>
              <operationHasOwnedParameters>
                <parameter Id="3a4faf8e-6d93-4940-add3-3a6bd81617fa" direction="Return" isUnique="false">
                  <elementDefinition Id="3a1d9697-8191-44dd-bee8-963cdcc9df90" />
                  <type_NamedElement>
                    <referencedTypeMoniker Id="d0e2218a-5be7-46cf-97a2-091e3a6a80e0" LastKnownName="decimal" />
                  </type_NamedElement>
                </parameter>
              </operationHasOwnedParameters>
            </ownedParameters>
          </operation>
          <operation Id="8a0ef611-d5ff-4ce3-844a-b2910c99d2e0" name="GetOrderLog" isLeaf="false" isStatic="false" isAbstract="false" concurrency="Sequential" isQuery="false">
            <elementDefinition Id="b0f7edd2-3e83-48a0-a78c-30f3c77a6c80" />
            <ownedParameters>
              <operationHasOwnedParameters>
                <parameter Id="134cadc0-aa27-4680-a4b5-0730f3a181ba" name="id" direction="In" isUnique="false">
                  <elementDefinition Id="287177c4-b8a9-43ef-9423-32b5313b5d78" />
                  <type_NamedElement>
                    <referencedTypeMoniker Id="de578a74-cb65-4d29-833c-4c0b903c29db" LastKnownName="int" />
                  </type_NamedElement>
                </parameter>
              </operationHasOwnedParameters>
              <operationHasOwnedParameters>
                <parameter Id="02b82923-fd44-4de8-8e4d-106b6fc75095" direction="Return" isUnique="false">
                  <elementDefinition Id="40b7fa49-a9ab-4008-bbd7-479a0bc098e2" />
                  <type_NamedElement>
                    <referencedTypeMoniker Id="a3d344e5-b1ee-4651-a6ac-7c3164dea949" LastKnownName="OrderLog" />
                  </type_NamedElement>
                </parameter>
              </operationHasOwnedParameters>
            </ownedParameters>
          </operation>
        </ownedOperationsInternal>
      </class>
    </logicalClassDesignerModelHasTypes>
    <logicalClassDesignerModelHasTypes>
      <class Id="cd276153-9c6d-4ebc-b0d1-a6e2838d7c37" name="Workshop" isAbstract="false" isLeaf="false" isActiveClass="false">
        <elementDefinition Id="28ff5777-9945-4014-a473-a590892f0d02" />
        <targetEnds>
          <association Id="d266b98d-29c1-4a97-87da-8d16a3a5a518" isDerived="false" sourceEndRoleName="Workshop" targetEndRoleName="Batch" isLeaf="false" isAbstract="false">
            <classMoniker Id="593cb2ed-8cab-400f-84d9-404853805b39" LastKnownName="Batch" />
            <relationshipOwnedElementsInternal>
              <associationHasOwnedEnds>
                <memberEnd Id="7b6114e8-a11b-4ab6-b5ac-7f7dbc9cd97b" name="Workshop" isLeaf="false" isStatic="false" isReadOnly="false" isDerived="false" isDerivedUnion="false" aggregation="Composite" isComposite="false" isNavigableOwned="false">
                  <elementDefinition Id="0f17953c-c64e-4761-98fd-7e5e3bde2de1" />
                </memberEnd>
              </associationHasOwnedEnds>
              <associationHasOwnedEnds>
                <memberEnd Id="c65df1a3-968d-4aa8-9b78-00b0cfd18a95" name="Batch" isLeaf="false" isStatic="false" isReadOnly="false" isDerived="false" isDerivedUnion="false" aggregation="None" isComposite="true">
                  <lowerValueInternal>
                    <literalString Id="54eb5157-3552-4249-9024-6b268b6c3319" name="Lower" value="0">
                      <elementDefinition Id="7ad96fbb-9b95-44f3-9dc3-e7d70c57a979" />
                    </literalString>
                  </lowerValueInternal>
                  <upperValueInternal>
                    <literalString Id="dd6aaec7-e3d4-4497-8ba0-a593468f45db" name="Upper" value="1">
                      <elementDefinition Id="5c7ce246-56af-4e28-9f40-5ed8de93666f" />
                    </literalString>
                  </upperValueInternal>
                  <elementDefinition Id="2c61cdcd-5021-4a3a-83cf-63b0729dd103" />
                </memberEnd>
              </associationHasOwnedEnds>
            </relationshipOwnedElementsInternal>
            <elementDefinition Id="835da845-011f-4c7d-a035-e011e1fc4508" />
          </association>
        </targetEnds>
        <ownedAttributesInternal>
          <property Id="3678996b-5053-48ba-ae11-afc573c5f91b" name="Location" isLeaf="false" isStatic="false" isReadOnly="false" isUnique="false" isDerived="false" isDerivedUnion="false" aggregation="None" isComposite="false">
            <elementDefinition Id="e29a762b-c4b7-4845-95b9-4bfff68e3fc7" />
            <type_NamedElement>
              <referencedTypeMoniker Id="5f136764-f9fe-423d-b193-2d5c0b1897f4" LastKnownName="String" />
            </type_NamedElement>
          </property>
          <property Id="d89cb1c9-fc4b-4ea7-9376-5588889fee0a" name="id" isLeaf="false" isStatic="false" isReadOnly="false" isUnique="false" isDerived="false" isDerivedUnion="false" aggregation="None" isComposite="false">
            <elementDefinition Id="2cae716f-26d9-4d55-9765-0467634a620a" />
            <type_NamedElement>
              <referencedTypeMoniker Id="13b549a6-70aa-477b-94d8-e8ab90df878c" LastKnownName="Integer" />
            </type_NamedElement>
          </property>
          <property Id="91ef6e72-c1ea-4ece-9219-35e05a0a91b7" name="DelTime" isLeaf="false" isStatic="false" isReadOnly="false" isUnique="false" isDerived="false" isDerivedUnion="false" aggregation="None" isComposite="false">
            <elementDefinition Id="395e0437-d08b-45e9-8bed-8b122cf9a6c6" />
            <type_NamedElement>
              <referencedTypeMoniker Id="5e95a766-896f-41c7-8951-778ddf708d7a" LastKnownName="DateTime" />
            </type_NamedElement>
          </property>
          <property Id="6d63db30-e725-43fc-b6a8-383924c28437" name="PhoneNum" isLeaf="false" isStatic="false" isReadOnly="false" isUnique="false" isDerived="false" isDerivedUnion="false" aggregation="None" isComposite="false">
            <elementDefinition Id="4e8c9828-4e62-4e73-a80f-c7f7960aa7b8" />
            <type_NamedElement>
              <referencedTypeMoniker Id="faf4849f-8756-4979-b0da-605e57790912" LastKnownName="String" />
            </type_NamedElement>
          </property>
        </ownedAttributesInternal>
        <ownedOperationsInternal>
          <operation Id="bc75691b-7786-47de-bb62-ea791906738e" name="CalcLoad" isLeaf="false" isStatic="false" isAbstract="false" concurrency="Sequential" isQuery="false">
            <elementDefinition Id="30c0a5e6-86ad-4fa5-9eda-c43179f159ff" />
            <ownedParameters>
              <operationHasOwnedParameters>
                <parameter Id="6b91a6e9-2976-4174-8c1d-9a9d5965b559" direction="Return" isUnique="false">
                  <elementDefinition Id="d4e5e8f7-00cc-4d10-b78c-1d8632015a4f" />
                  <type_NamedElement>
                    <referencedTypeMoniker Id="5655a02a-7ae5-4a44-9419-3de5361f9934" LastKnownName="double" />
                  </type_NamedElement>
                </parameter>
              </operationHasOwnedParameters>
              <operationHasOwnedParameters>
                <parameter Id="2de767fa-cabc-49de-9354-bd3e3021bd90" name="from" direction="In" isUnique="false">
                  <elementDefinition Id="b9f8d15e-88b6-4de8-a00e-ee4972501e17" />
                  <type_NamedElement>
                    <referencedTypeMoniker Id="5e95a766-896f-41c7-8951-778ddf708d7a" LastKnownName="DateTime" />
                  </type_NamedElement>
                </parameter>
              </operationHasOwnedParameters>
              <operationHasOwnedParameters>
                <parameter Id="0607423c-a727-4c3c-a749-dec86aa972b1" name="until" direction="In" isUnique="false">
                  <elementDefinition Id="d78181d3-efe8-4da3-a03f-4b2166404454" />
                  <type_NamedElement>
                    <referencedTypeMoniker Id="5e95a766-896f-41c7-8951-778ddf708d7a" LastKnownName="DateTime" />
                  </type_NamedElement>
                </parameter>
              </operationHasOwnedParameters>
            </ownedParameters>
          </operation>
          <operation Id="aeb00278-d030-475b-8d64-5aea0e252634" name="AddWorkshop" isLeaf="false" isStatic="false" isAbstract="false" concurrency="Sequential" isQuery="false">
            <elementDefinition Id="dafaf4a1-5d02-4847-b300-b43ecc6b1468" />
            <ownedParameters>
              <operationHasOwnedParameters>
                <parameter Id="f9add55f-06b4-4ee3-bfe2-4276c6c66868" direction="Return" isUnique="false">
                  <elementDefinition Id="bbe545a4-bf4d-44d9-8150-8ba27fa860b0" />
                  <type_NamedElement>
                    <referencedTypeMoniker Id="6a45fed8-1689-4fa9-8e39-f876365db554" LastKnownName="bool" />
                  </type_NamedElement>
                </parameter>
              </operationHasOwnedParameters>
            </ownedParameters>
          </operation>
          <operation Id="f29f36a5-50c7-42db-8a95-60208aaba2fb" name="EditWorkshop" isLeaf="false" isStatic="false" isAbstract="false" concurrency="Sequential" isQuery="false">
            <elementDefinition Id="c3a50585-5dae-418b-908b-f1bc161d4942" />
            <ownedParameters>
              <operationHasOwnedParameters>
                <parameter Id="30f4f4ec-45e2-4a51-8592-b5686527ff52" direction="Return" isUnique="false">
                  <elementDefinition Id="81886877-efdf-4f72-863d-f92fd467de8f" />
                  <type_NamedElement>
                    <referencedTypeMoniker Id="6a45fed8-1689-4fa9-8e39-f876365db554" LastKnownName="bool" />
                  </type_NamedElement>
                </parameter>
              </operationHasOwnedParameters>
            </ownedParameters>
          </operation>
          <operation Id="2a460994-dfc2-482c-a814-068093ccf076" name="DelWorkshop" isLeaf="false" isStatic="false" isAbstract="false" concurrency="Sequential" isQuery="false">
            <elementDefinition Id="f1abacb4-4f39-401b-a1c6-9f438be8a862" />
            <ownedParameters>
              <operationHasOwnedParameters>
                <parameter Id="367c22bf-3f03-4e89-beeb-d161c4a4bcf9" direction="Return" isUnique="false">
                  <elementDefinition Id="895416d2-cc61-43d2-b443-6bb859802fc1" />
                  <type_NamedElement>
                    <referencedTypeMoniker Id="6a45fed8-1689-4fa9-8e39-f876365db554" LastKnownName="bool" />
                  </type_NamedElement>
                </parameter>
              </operationHasOwnedParameters>
            </ownedParameters>
          </operation>
          <operation Id="ff7386ef-cb9e-4443-aefa-88113c135794" name="Workshop" isLeaf="false" isStatic="false" isAbstract="false" concurrency="Sequential" isQuery="false">
            <elementDefinition Id="743f0028-ef42-4b5b-977d-e338d13ca91c" />
            <ownedParameters>
              <operationHasOwnedParameters>
                <parameter Id="edecd287-ddba-4939-9eae-5f6c4e9d91b3" direction="Return" isUnique="false">
                  <elementDefinition Id="17c071ef-3005-45c6-a204-be472fea3514" />
                  <type_NamedElement>
                    <referencedTypeMoniker Id="62e1c591-1fc8-4d49-889d-ba3d80faa959" LastKnownName="void" />
                  </type_NamedElement>
                </parameter>
              </operationHasOwnedParameters>
            </ownedParameters>
          </operation>
          <operation Id="09b9545c-a949-46f5-b0ea-2ec447f98372" name="GetValidTimetable" isLeaf="false" isStatic="false" isAbstract="false" concurrency="Sequential" isQuery="false">
            <elementDefinition Id="ea9229ee-f432-404d-9248-89a185866a68" />
            <ownedParameters>
              <operationHasOwnedParameters>
                <parameter Id="fd4f2125-548f-48c0-9409-fb4a90d67136" direction="Return" isUnique="false">
                  <elementDefinition Id="a9f6fa82-30ec-48b1-a093-552cd90ae304" />
                  <type_NamedElement>
                    <referencedTypeMoniker Id="04c69843-b4ee-48ec-984a-fbaa08a042e5" LastKnownName="WorkshopTimetable" />
                  </type_NamedElement>
                </parameter>
              </operationHasOwnedParameters>
            </ownedParameters>
          </operation>
          <operation Id="6618dc04-b178-4ab1-9891-57409a8b8449" name="GetTimetables" isLeaf="false" isStatic="false" isAbstract="false" concurrency="Sequential" isQuery="false">
            <elementDefinition Id="f4299d1f-f596-4860-aae8-e446fb5106eb" />
            <ownedParameters>
              <operationHasOwnedParameters>
                <parameter Id="2afa5f6d-aecd-44f0-922e-41d8b5a326c3" direction="Return" isUnique="false">
                  <elementDefinition Id="85f89424-1ec7-4801-b337-4dc04cccd976" />
                  <type_NamedElement>
                    <referencedTypeMoniker Id="a504101a-fcd4-4855-ab99-405c7225b8c5" LastKnownName="List&lt;WorkshopTimetable&gt;" />
                  </type_NamedElement>
                </parameter>
              </operationHasOwnedParameters>
              <operationHasOwnedParameters>
                <parameter Id="485f45e7-72e4-4831-8ef3-85def6c6a4ca" name="page" direction="In" isUnique="false">
                  <elementDefinition Id="c37ae94a-853b-433f-9737-3252d5282ce6" />
                  <type_NamedElement>
                    <referencedTypeMoniker Id="de578a74-cb65-4d29-833c-4c0b903c29db" LastKnownName="int" />
                  </type_NamedElement>
                </parameter>
              </operationHasOwnedParameters>
              <operationHasOwnedParameters>
                <parameter Id="cd817625-eab6-4b7d-9795-6af059f0e79d" name="count" direction="In" isUnique="false">
                  <elementDefinition Id="3c60a0f1-3911-4624-835c-71004cd0d070" />
                  <type_NamedElement>
                    <referencedTypeMoniker Id="de578a74-cb65-4d29-833c-4c0b903c29db" LastKnownName="int" />
                  </type_NamedElement>
                </parameter>
              </operationHasOwnedParameters>
              <operationHasOwnedParameters>
                <parameter Id="e4d54d13-14ea-4e5e-b790-0279189bc54d" name="from" direction="In" isUnique="false">
                  <elementDefinition Id="cab94d1c-a7fe-4d3a-86c3-07cc53e612df" />
                  <type_NamedElement>
                    <referencedTypeMoniker Id="5e95a766-896f-41c7-8951-778ddf708d7a" LastKnownName="DateTime" />
                  </type_NamedElement>
                </parameter>
              </operationHasOwnedParameters>
              <operationHasOwnedParameters>
                <parameter Id="caf5f214-aec2-4757-9508-8ac0dcc2329b" name="until" direction="In" isUnique="false">
                  <elementDefinition Id="333198f2-a0b6-4027-9c7b-a3f67f1bc332" />
                  <type_NamedElement>
                    <referencedTypeMoniker Id="5e95a766-896f-41c7-8951-778ddf708d7a" LastKnownName="DateTime" />
                  </type_NamedElement>
                </parameter>
              </operationHasOwnedParameters>
            </ownedParameters>
          </operation>
          <operation Id="bb8c138a-116c-44cd-bc9a-17c590b180fc" name="CalcProfit" isLeaf="false" isStatic="false" isAbstract="false" concurrency="Sequential" isQuery="false">
            <elementDefinition Id="f724ab30-0566-447c-9be1-ae6f0837de15" />
            <ownedParameters>
              <operationHasOwnedParameters>
                <parameter Id="48660259-d405-456f-b8bf-5ec2f3458a3b" name="from" direction="In" isUnique="false">
                  <elementDefinition Id="e9453c15-a5a2-4f42-9e25-59221c8c163b" />
                  <type_NamedElement>
                    <referencedTypeMoniker Id="5e95a766-896f-41c7-8951-778ddf708d7a" LastKnownName="DateTime" />
                  </type_NamedElement>
                </parameter>
              </operationHasOwnedParameters>
              <operationHasOwnedParameters>
                <parameter Id="69e17b72-efca-41fe-8c9f-c7c20b8dfe56" name="until" direction="In" isUnique="false">
                  <elementDefinition Id="0326a78d-7c1b-42e1-8662-13d9f486086f" />
                  <type_NamedElement>
                    <referencedTypeMoniker Id="5e95a766-896f-41c7-8951-778ddf708d7a" LastKnownName="DateTime" />
                  </type_NamedElement>
                </parameter>
              </operationHasOwnedParameters>
              <operationHasOwnedParameters>
                <parameter Id="c5e09eff-81c3-48d2-83a8-c56d8910517d" direction="Return" isUnique="false">
                  <elementDefinition Id="16df8967-f165-4d4f-8044-f6725348b6eb" />
                  <type_NamedElement>
                    <referencedTypeMoniker Id="d0e2218a-5be7-46cf-97a2-091e3a6a80e0" LastKnownName="decimal" />
                  </type_NamedElement>
                </parameter>
              </operationHasOwnedParameters>
            </ownedParameters>
          </operation>
        </ownedOperationsInternal>
      </class>
    </logicalClassDesignerModelHasTypes>
    <packageHasNamedElement>
      <referencedType Id="5f136764-f9fe-423d-b193-2d5c0b1897f4" name="String" isAbstract="false" isLeaf="false" cachedFullName="String">
        <elementDefinition Id="59259974-6d55-42c6-b7bd-763d77ac8ef9" />
      </referencedType>
    </packageHasNamedElement>
    <packageHasNamedElement>
      <referencedType Id="db23d9b0-c078-44b6-873c-562eb77533cc" name="List&lt;Master&gt;" isAbstract="false" isLeaf="false" cachedFullName="List&lt;Master&gt;">
        <elementDefinition Id="507270b5-965e-421d-bb76-6c2f6f446eac" />
      </referencedType>
    </packageHasNamedElement>
    <packageHasNamedElement>
      <referencedType Id="f4c65483-48fa-48c6-b1ba-774306746da9" name="Workshop" isAbstract="false" isLeaf="false" cachedFullName="CompServiceClassDiagram::Workshop">
        <elementDefinition Id="28ff5777-9945-4014-a473-a590892f0d02" />
      </referencedType>
    </packageHasNamedElement>
    <packageHasNamedElement>
      <referencedType Id="1442db07-e3d8-4e3c-947e-806505dd7130" name="List&lt;Order&gt;" isAbstract="false" isLeaf="false" cachedFullName="List&lt;Order&gt;">
        <elementDefinition Id="e191bb0c-ba43-4f6d-a57a-7e1165aa2389" />
      </referencedType>
    </packageHasNamedElement>
    <packageHasNamedElement>
      <referencedType Id="0082579e-04fe-43f7-a6b8-d2994e95b3d6" name="Integer" isAbstract="false" isLeaf="false" cachedFullName="Integer">
        <elementDefinition Id="220a3521-e091-4221-bae9-3ef9018e845c" />
      </referencedType>
    </packageHasNamedElement>
    <packageHasNamedElement>
      <referencedType Id="7fb7c93f-995a-4b07-94af-09f2896d270c" name="Client" isAbstract="false" isLeaf="false" cachedFullName="CompServiceClassDiagram::Client">
        <elementDefinition Id="3cbddadd-d029-40c3-b045-8bccb04a6bc8" />
      </referencedType>
    </packageHasNamedElement>
    <packageHasNamedElement>
      <referencedType Id="603e91ec-7198-40f7-a47d-8e53c0e49d75" name="Product" isAbstract="false" isLeaf="false" cachedFullName="CompServiceClassDiagram::Product">
        <elementDefinition Id="57480d6f-b872-4e75-b996-e8207e616f49" />
      </referencedType>
    </packageHasNamedElement>
    <packageHasNamedElement>
      <referencedType Id="4c13560b-accc-4537-a466-aff55cd8e227" name="Master" isAbstract="false" isLeaf="false" cachedFullName="CompServiceClassDiagram::Master">
        <elementDefinition Id="939286e1-c9aa-47d9-ad7b-458d2a0f2614" />
      </referencedType>
    </packageHasNamedElement>
    <packageHasNamedElement>
      <referencedType Id="5e95a766-896f-41c7-8951-778ddf708d7a" name="DateTime" isAbstract="false" isLeaf="false" cachedFullName="DateTime">
        <elementDefinition Id="6f1e3583-6453-46eb-9e38-2685f90d378f" />
      </referencedType>
    </packageHasNamedElement>
    <packageHasNamedElement>
      <referencedType Id="25fea15f-c0c7-47ea-b7b4-c6007a2f6e20" name="Manager" isAbstract="false" isLeaf="false" cachedFullName="CompServiceClassDiagram::Manager">
        <elementDefinition Id="7185b57f-ed0d-487e-a875-3d0c08bdef1f" />
      </referencedType>
    </packageHasNamedElement>
    <logicalClassDesignerModelHasTypes>
      <class Id="a0b4b3c5-1f5f-45d8-b541-883444a0c2a7" name="ClientsList {static}" isAbstract="false" isLeaf="false" isActiveClass="false">
        <elementDefinition Id="0b252353-4b82-4926-b884-4e3fbd2165e7" />
        <targetEnds>
          <association Id="e3e2d093-614c-41c5-a3e3-2bd74ace9d41" isDerived="false" sourceEndRoleName="ClientsList {static}" targetEndRoleName="Client" isLeaf="false" isAbstract="false">
            <classMoniker Id="a5c00f8f-2e99-4e50-af3d-5016ef70a856" LastKnownName="Client" />
            <relationshipOwnedElementsInternal>
              <associationHasOwnedEnds>
                <memberEnd Id="c4e0f03b-ddcf-43c7-bfa0-58677426ce31" name="ClientsList {static}" isLeaf="false" isStatic="false" isReadOnly="false" isDerived="false" isDerivedUnion="false" aggregation="Shared" isComposite="false" isNavigableOwned="false">
                  <elementDefinition Id="cc437f96-ffc4-4959-afef-5d55dfc06743" />
                </memberEnd>
              </associationHasOwnedEnds>
              <associationHasOwnedEnds>
                <memberEnd Id="54b251ac-af00-4c0d-8e1c-ae988ab5b87f" name="Client" isLeaf="false" isStatic="false" isReadOnly="false" isDerived="false" isDerivedUnion="false" aggregation="None" isComposite="false">
                  <lowerValueInternal>
                    <literalString Id="b890de16-41ff-4761-9767-b3e22656043b" name="Lower" value="1">
                      <elementDefinition Id="38ae84e3-7866-4221-9cb2-c20064380d40" />
                    </literalString>
                  </lowerValueInternal>
                  <upperValueInternal>
                    <literalString Id="9cf56ddd-e3d9-4990-aa10-51fd263fc1fd" name="Upper" value="*">
                      <elementDefinition Id="fb60ce27-eb63-4c88-8910-ce4007305e3d" />
                    </literalString>
                  </upperValueInternal>
                  <elementDefinition Id="2c4f1c5f-8780-4bce-a87e-62f11ccc85b2" />
                </memberEnd>
              </associationHasOwnedEnds>
            </relationshipOwnedElementsInternal>
            <elementDefinition Id="a2e61f1e-c114-4bcd-8357-3a9c8f245ddc" />
          </association>
        </targetEnds>
        <ownedOperationsInternal>
          <operation Id="d1a6b685-c6d4-4aa9-aee7-830853c0f4a1" name="GetClients" isLeaf="false" isStatic="true" isAbstract="false" concurrency="Sequential" isQuery="false">
            <elementDefinition Id="f85dcd23-bfc9-4e50-bf56-6ddc1cc40b1c" />
            <ownedParameters>
              <operationHasOwnedParameters>
                <parameter Id="37fee742-9759-461a-8820-b92ddf8e9688" direction="Return" isUnique="false">
                  <elementDefinition Id="5e4554fc-17ee-450f-8030-4386067ff6c8" />
                  <type_NamedElement>
                    <referencedTypeMoniker Id="e49c4433-1fb9-4c3f-9066-c702d9baa8e5" LastKnownName="List&lt;Client&gt;" />
                  </type_NamedElement>
                </parameter>
              </operationHasOwnedParameters>
              <operationHasOwnedParameters>
                <parameter Id="a655e43f-f9d7-4dd1-b448-6d0ea6f9565b" name="filterA" direction="In" isUnique="false">
                  <elementDefinition Id="9f55bcad-f9ea-4157-b323-135e424ea7a3" />
                  <type_NamedElement>
                    <referencedTypeMoniker Id="7fb7c93f-995a-4b07-94af-09f2896d270c" LastKnownName="Client" />
                  </type_NamedElement>
                </parameter>
              </operationHasOwnedParameters>
              <operationHasOwnedParameters>
                <parameter Id="a5644221-0bdb-4c02-b20e-3e3474e19e6c" name="ordersFrom" direction="In" isUnique="false">
                  <elementDefinition Id="2e9951c0-9539-4d0b-9f0d-657ceddbe87c" />
                  <type_NamedElement>
                    <referencedTypeMoniker Id="de578a74-cb65-4d29-833c-4c0b903c29db" LastKnownName="int" />
                  </type_NamedElement>
                </parameter>
              </operationHasOwnedParameters>
              <operationHasOwnedParameters>
                <parameter Id="60eeec3a-baab-47cc-9165-6c3689ead031" name="ordersUntil" direction="In" isUnique="false">
                  <elementDefinition Id="7455a683-6c91-4fd1-85be-cce882deb376" />
                  <type_NamedElement>
                    <referencedTypeMoniker Id="de578a74-cb65-4d29-833c-4c0b903c29db" LastKnownName="int" />
                  </type_NamedElement>
                </parameter>
              </operationHasOwnedParameters>
              <operationHasOwnedParameters>
                <parameter Id="03dc65ac-0d2b-4e4b-9fc4-05e406db87ff" name="sortBy" direction="In" isUnique="false">
                  <elementDefinition Id="ff4c0aac-6a3f-4f4a-89e4-84ebb53eff1a" />
                  <type_NamedElement>
                    <referencedTypeMoniker Id="5432db89-8420-4f3f-bf54-d2b10dcc16ad" LastKnownName="string" />
                  </type_NamedElement>
                </parameter>
              </operationHasOwnedParameters>
              <operationHasOwnedParameters>
                <parameter Id="4716dfd8-1c50-4d0c-a1db-842bb037a009" name="count" direction="In" isUnique="false">
                  <elementDefinition Id="7c5d410d-1cba-4669-b9cc-602b9da22af3" />
                  <type_NamedElement>
                    <referencedTypeMoniker Id="de578a74-cb65-4d29-833c-4c0b903c29db" LastKnownName="int" />
                  </type_NamedElement>
                </parameter>
              </operationHasOwnedParameters>
              <operationHasOwnedParameters>
                <parameter Id="6132a7d5-1ba5-44c0-aa03-1ed62684ca15" name="desk" direction="In" isUnique="false">
                  <elementDefinition Id="b737c83e-1fd1-40a0-a4af-139bc2471202" />
                  <type_NamedElement>
                    <referencedTypeMoniker Id="6a45fed8-1689-4fa9-8e39-f876365db554" LastKnownName="bool" />
                  </type_NamedElement>
                </parameter>
              </operationHasOwnedParameters>
              <operationHasOwnedParameters>
                <parameter Id="8ce89d2f-129a-4172-8183-0141c4b53243" name="page" direction="In" isUnique="false">
                  <elementDefinition Id="e200b44e-b32b-4087-a28a-7fd63a8ec042" />
                  <type_NamedElement>
                    <referencedTypeMoniker Id="de578a74-cb65-4d29-833c-4c0b903c29db" LastKnownName="int" />
                  </type_NamedElement>
                </parameter>
              </operationHasOwnedParameters>
            </ownedParameters>
          </operation>
          <operation Id="06fa7a8a-2c5f-4013-bdcf-70e1362fa0ba" name="GetById" isLeaf="false" isStatic="true" isAbstract="false" concurrency="Sequential" isQuery="false">
            <elementDefinition Id="e4bbc939-55fe-4ef2-b704-01c1cc55abf4" />
            <ownedParameters>
              <operationHasOwnedParameters>
                <parameter Id="0f8d1085-5015-4027-80bd-6020ef8942a5" name="Int" direction="In" isUnique="false">
                  <elementDefinition Id="4f7195dd-2fa7-457f-80c8-f0e9831a2ec7" />
                </parameter>
              </operationHasOwnedParameters>
              <operationHasOwnedParameters>
                <parameter Id="bf0a6968-24b0-4676-be1e-a65978aa2186" direction="Return" isUnique="false">
                  <elementDefinition Id="d5de954c-3e5c-483d-bfe4-cc7b019dede6" />
                  <type_NamedElement>
                    <referencedTypeMoniker Id="7fb7c93f-995a-4b07-94af-09f2896d270c" LastKnownName="Client" />
                  </type_NamedElement>
                </parameter>
              </operationHasOwnedParameters>
            </ownedParameters>
          </operation>
        </ownedOperationsInternal>
      </class>
    </logicalClassDesignerModelHasTypes>
    <packageHasNamedElement>
      <referencedType Id="62e1c591-1fc8-4d49-889d-ba3d80faa959" name="void" isAbstract="false" isLeaf="false" cachedFullName="void">
        <elementDefinition Id="96d274f9-94d3-40c5-bc6d-9f61b50251a3" />
      </referencedType>
    </packageHasNamedElement>
    <packageHasNamedElement>
      <referencedType Id="6a45fed8-1689-4fa9-8e39-f876365db554" name="bool" isAbstract="false" isLeaf="false" cachedFullName="bool">
        <elementDefinition Id="9b3d5d60-324b-4301-b8f5-3750227e268c" />
      </referencedType>
    </packageHasNamedElement>
    <packageHasNamedElement>
      <referencedType Id="de578a74-cb65-4d29-833c-4c0b903c29db" name="int" isAbstract="false" isLeaf="false" cachedFullName="int">
        <elementDefinition Id="f984419c-cfc8-4466-a4ac-951b45074e3f" />
      </referencedType>
    </packageHasNamedElement>
    <packageHasNamedElement>
      <referencedType Id="5655a02a-7ae5-4a44-9419-3de5361f9934" name="double" isAbstract="false" isLeaf="false" cachedFullName="double">
        <elementDefinition Id="e8ebf5e8-de13-45f5-8443-aae752a51d1b" />
      </referencedType>
    </packageHasNamedElement>
    <packageHasNamedElement>
      <referencedType Id="1e420cc7-7f2d-47cc-88d5-5aad23d5e842" name="List&lt;Service&gt;" isAbstract="false" isLeaf="false" cachedFullName="List&lt;Service&gt;">
        <elementDefinition Id="77ddbafd-ca7b-4f67-9c70-6959f515277d" />
      </referencedType>
    </packageHasNamedElement>
    <packageHasNamedElement>
      <referencedType Id="5432db89-8420-4f3f-bf54-d2b10dcc16ad" name="string" isAbstract="false" isLeaf="false" cachedFullName="string">
        <elementDefinition Id="74cafbae-7254-4f6c-9322-6709f1fee30e" />
      </referencedType>
    </packageHasNamedElement>
    <packageHasNamedElement>
      <referencedType Id="e49c4433-1fb9-4c3f-9066-c702d9baa8e5" name="List&lt;Client&gt;" isAbstract="false" isLeaf="false" cachedFullName="List&lt;Client&gt;">
        <elementDefinition Id="2f6a8388-8091-4b82-8575-62926d3899c9" />
      </referencedType>
    </packageHasNamedElement>
    <packageHasNamedElement>
      <referencedType Id="ac7623ae-b99e-4f32-9a25-c48536fdf8c0" name="string" isAbstract="false" isLeaf="false" cachedFullName="string">
        <elementDefinition Id="74cafbae-7254-4f6c-9322-6709f1fee30e" />
      </referencedType>
    </packageHasNamedElement>
    <packageHasNamedElement>
      <referencedType Id="28e6531d-21c0-4784-b8ec-a3932d65441f" name="int" isAbstract="false" isLeaf="false" cachedFullName="int">
        <elementDefinition Id="f984419c-cfc8-4466-a4ac-951b45074e3f" />
      </referencedType>
    </packageHasNamedElement>
    <logicalClassDesignerModelHasTypes>
      <class Id="98656d28-e349-46b6-a695-878ec8661df3" name="ManagersList {static}" isAbstract="false" isLeaf="false" isActiveClass="false">
        <elementDefinition Id="1654dbe6-1366-4f11-ac7e-d584ea815e16" />
        <targetEnds>
          <association Id="6f5e8c72-f2e5-43b9-a8ec-4166f766c6bd" isDerived="false" sourceEndRoleName="ManagersList {static}" targetEndRoleName="Manager" isLeaf="false" isAbstract="false">
            <classMoniker Id="b6856be0-2a50-4617-a0c0-c385060eb4f9" LastKnownName="Manager" />
            <relationshipOwnedElementsInternal>
              <associationHasOwnedEnds>
                <memberEnd Id="9839125d-7018-4658-8691-21d3cae33e0a" name="ManagersList {static}" isLeaf="false" isStatic="false" isReadOnly="false" isDerived="false" isDerivedUnion="false" aggregation="Shared" isComposite="false" isNavigableOwned="false">
                  <elementDefinition Id="a798ccad-d1d6-46cb-9500-c234a9b67191" />
                </memberEnd>
              </associationHasOwnedEnds>
              <associationHasOwnedEnds>
                <memberEnd Id="01d2e6a5-71c2-4004-ae6e-a7cc6b0580ab" name="Manager" isLeaf="false" isStatic="false" isReadOnly="false" isDerived="false" isDerivedUnion="false" aggregation="None" isComposite="false">
                  <lowerValueInternal>
                    <literalString Id="ae5e9c2b-bd64-4fec-bef6-2cc723452f56" name="Lower" value="1">
                      <elementDefinition Id="323637ac-02ef-4d41-80eb-c101216d2b4f" />
                    </literalString>
                  </lowerValueInternal>
                  <upperValueInternal>
                    <literalString Id="5c1d7e96-dc2d-4701-926e-c8f97d4c4ce2" name="Upper" value="*">
                      <elementDefinition Id="a50283b6-0001-4d97-a496-19a6619cbb7f" />
                    </literalString>
                  </upperValueInternal>
                  <elementDefinition Id="d35a2dd2-1876-4878-8619-caac8309ecc7" />
                </memberEnd>
              </associationHasOwnedEnds>
            </relationshipOwnedElementsInternal>
            <elementDefinition Id="68e4d762-7c2a-408c-88b1-02608299c900" />
          </association>
        </targetEnds>
        <ownedOperationsInternal>
          <operation Id="8f95f305-0b5f-45f9-857c-a6f07e9ec4a3" name="GetCManagers" isLeaf="false" isStatic="true" isAbstract="false" concurrency="Sequential" isQuery="false">
            <elementDefinition Id="81c6ae8c-bbbb-47df-813d-79b8ea6dcbe2" />
            <ownedParameters>
              <operationHasOwnedParameters>
                <parameter Id="8541919b-0a61-41f4-8918-6f8493f96909" direction="Return" isUnique="false">
                  <elementDefinition Id="9a81548a-d6e5-46ea-9163-56858bcb9c1b" />
                  <type_NamedElement>
                    <referencedTypeMoniker Id="3ef2da5a-6889-4914-aec7-a587bd38e5b3" LastKnownName="List&lt;Manager&gt;" />
                  </type_NamedElement>
                </parameter>
              </operationHasOwnedParameters>
              <operationHasOwnedParameters>
                <parameter Id="fa303056-7e8d-40af-9374-b7f55117eaec" name="ilterA" direction="In" isUnique="false">
                  <elementDefinition Id="970b0706-55c0-46b3-a070-1ce2ff8a0ac6" />
                  <type_NamedElement>
                    <referencedTypeMoniker Id="25fea15f-c0c7-47ea-b7b4-c6007a2f6e20" LastKnownName="Manager" />
                  </type_NamedElement>
                </parameter>
              </operationHasOwnedParameters>
              <operationHasOwnedParameters>
                <parameter Id="d25963cb-861d-431c-9bb9-da0d4da4dc2d" name="filterB" direction="In" isUnique="false">
                  <elementDefinition Id="b48cb1e2-d1d8-4432-9b99-7c96cea38711" />
                  <type_NamedElement>
                    <referencedTypeMoniker Id="25fea15f-c0c7-47ea-b7b4-c6007a2f6e20" LastKnownName="Manager" />
                  </type_NamedElement>
                </parameter>
              </operationHasOwnedParameters>
              <operationHasOwnedParameters>
                <parameter Id="5d0da7e0-f0f3-4f72-a8ef-606e0ea296e7" name="sortBy" direction="In" isUnique="false">
                  <elementDefinition Id="8c146c60-08ea-4fbc-988a-fc8cc4597613" />
                  <type_NamedElement>
                    <referencedTypeMoniker Id="ac7623ae-b99e-4f32-9a25-c48536fdf8c0" LastKnownName="string" />
                  </type_NamedElement>
                </parameter>
              </operationHasOwnedParameters>
              <operationHasOwnedParameters>
                <parameter Id="af0dae94-dfe6-4fad-b5bd-0a3cf79a9550" name="desk" direction="In" isUnique="false">
                  <elementDefinition Id="4cd75726-57f9-4df5-939f-8789a6d33a6f" />
                  <type_NamedElement>
                    <referencedTypeMoniker Id="6a45fed8-1689-4fa9-8e39-f876365db554" LastKnownName="bool" />
                  </type_NamedElement>
                </parameter>
              </operationHasOwnedParameters>
              <operationHasOwnedParameters>
                <parameter Id="dd85ddb5-8899-4e8d-bd27-f5f23b3b2d8f" name="fcount" direction="In" isUnique="false">
                  <elementDefinition Id="cd76dd9c-e2b9-4d01-baab-9e23aab9fa04" />
                  <type_NamedElement>
                    <referencedTypeMoniker Id="28e6531d-21c0-4784-b8ec-a3932d65441f" LastKnownName="int" />
                  </type_NamedElement>
                </parameter>
              </operationHasOwnedParameters>
              <operationHasOwnedParameters>
                <parameter Id="e9154e3c-3433-4adf-bec7-75a794ddf394" name="page" direction="In" isUnique="false">
                  <elementDefinition Id="d54520fb-1c9f-4f66-b132-c9d2ce2a7227" />
                  <type_NamedElement>
                    <referencedTypeMoniker Id="de578a74-cb65-4d29-833c-4c0b903c29db" LastKnownName="int" />
                  </type_NamedElement>
                </parameter>
              </operationHasOwnedParameters>
            </ownedParameters>
          </operation>
          <operation Id="c0879258-2d5b-4321-aa0a-001a591594ca" name="GetById" isLeaf="false" isStatic="true" isAbstract="false" concurrency="Sequential" isQuery="false">
            <elementDefinition Id="5982680d-e210-415b-ba31-2408df9ec1bf" />
            <ownedParameters>
              <operationHasOwnedParameters>
                <parameter Id="0eb8c4c5-862e-4e4b-aa00-20b630263187" direction="Return" isUnique="false">
                  <elementDefinition Id="b76bb77f-de20-465e-806a-f3168334fba3" />
                  <type_NamedElement>
                    <referencedTypeMoniker Id="25fea15f-c0c7-47ea-b7b4-c6007a2f6e20" LastKnownName="Manager" />
                  </type_NamedElement>
                </parameter>
              </operationHasOwnedParameters>
              <operationHasOwnedParameters>
                <parameter Id="89f22b26-d296-4d83-b7a8-7f0d090d0e60" name="Int" direction="In" isUnique="false">
                  <elementDefinition Id="b2514d15-e161-40a6-84ec-5a2c09cdf803" />
                </parameter>
              </operationHasOwnedParameters>
            </ownedParameters>
          </operation>
        </ownedOperationsInternal>
      </class>
    </logicalClassDesignerModelHasTypes>
    <packageHasNamedElement>
      <referencedType Id="d5ee5cab-70a9-4944-bce8-bc63a90bc18b" name="string" isAbstract="false" isLeaf="false" cachedFullName="string">
        <elementDefinition Id="74cafbae-7254-4f6c-9322-6709f1fee30e" />
      </referencedType>
    </packageHasNamedElement>
    <packageHasNamedElement>
      <referencedType Id="2f44e82c-bed6-4a5e-86eb-47ad3618f426" name="int" isAbstract="false" isLeaf="false" cachedFullName="int">
        <elementDefinition Id="f984419c-cfc8-4466-a4ac-951b45074e3f" />
      </referencedType>
    </packageHasNamedElement>
    <logicalClassDesignerModelHasTypes>
      <class Id="5ca65296-85bb-4e0c-b9d1-b14942987f6b" name="MastersList {static}" isAbstract="false" isLeaf="false" isActiveClass="false">
        <elementDefinition Id="bed1ff95-ea9e-4f79-945a-7d2ec53d0729" />
        <targetEnds>
          <association Id="9ea92e97-b135-4d3b-b00a-bab1e7555428" isDerived="false" sourceEndRoleName="MastersList {static}" targetEndRoleName="Master" isLeaf="false" isAbstract="false">
            <classMoniker Id="f87435e5-83d1-45e9-8965-813f6d8a5e7d" LastKnownName="Master" />
            <relationshipOwnedElementsInternal>
              <associationHasOwnedEnds>
                <memberEnd Id="8a767599-a849-42a9-8ec8-27d61aedffbc" name="MastersList {static}" isLeaf="false" isStatic="false" isReadOnly="false" isDerived="false" isDerivedUnion="false" aggregation="Shared" isComposite="false" isNavigableOwned="false">
                  <elementDefinition Id="2256ef63-f778-4cf9-a5f6-0aef977e20cd" />
                </memberEnd>
              </associationHasOwnedEnds>
              <associationHasOwnedEnds>
                <memberEnd Id="8a5776f9-e0f0-44cb-9d6f-012d3543c4e6" name="Master" isLeaf="false" isStatic="false" isReadOnly="false" isDerived="false" isDerivedUnion="false" aggregation="None" isComposite="false">
                  <lowerValueInternal>
                    <literalString Id="0a307c50-886c-4a81-ac17-073bde9423c7" name="Lower" value="1">
                      <elementDefinition Id="57613ab2-e8b2-49ca-9223-a35c6e56b711" />
                    </literalString>
                  </lowerValueInternal>
                  <upperValueInternal>
                    <literalString Id="90a43810-de4a-4ec1-aeda-71d5218a8b54" name="Upper" value="*">
                      <elementDefinition Id="5ff6ee92-6c7a-48d2-a8fd-6ec1e6029584" />
                    </literalString>
                  </upperValueInternal>
                  <elementDefinition Id="d46b4dda-0774-43a5-a8a4-202e180dde72" />
                </memberEnd>
              </associationHasOwnedEnds>
            </relationshipOwnedElementsInternal>
            <elementDefinition Id="d71a3dff-090e-4328-848e-937b62615fa7" />
          </association>
        </targetEnds>
        <ownedOperationsInternal>
          <operation Id="96880432-3a5b-4332-b523-1c2ee256a23b" name="GetMasters" isLeaf="false" isStatic="true" isAbstract="false" concurrency="Sequential" isQuery="false">
            <elementDefinition Id="142dfd12-ee64-47fd-a9f5-c5d0d6a65ecb" />
            <ownedParameters>
              <operationHasOwnedParameters>
                <parameter Id="e68ea0c6-8220-4814-84d6-19bbea1b650e" direction="Return" isUnique="false">
                  <elementDefinition Id="c1665c29-959d-46e1-b04b-d76bc6f8acf6" />
                  <type_NamedElement>
                    <referencedTypeMoniker Id="db23d9b0-c078-44b6-873c-562eb77533cc" LastKnownName="List&lt;Master&gt;" />
                  </type_NamedElement>
                </parameter>
              </operationHasOwnedParameters>
              <operationHasOwnedParameters>
                <parameter Id="b25d1069-25fb-43e0-ba5e-5b089f4518d9" name="filterA" direction="In" isUnique="false">
                  <elementDefinition Id="98dd6689-2d1d-4d44-92a0-71d2fded6a7e" />
                  <type_NamedElement>
                    <referencedTypeMoniker Id="4c13560b-accc-4537-a466-aff55cd8e227" LastKnownName="Master" />
                  </type_NamedElement>
                </parameter>
              </operationHasOwnedParameters>
              <operationHasOwnedParameters>
                <parameter Id="466cf2ae-3926-46cd-9bcc-e384d6aa7908" name="filterB" direction="In" isUnique="false">
                  <elementDefinition Id="9b768d8d-125a-4b25-ab27-750c6e68ae94" />
                  <type_NamedElement>
                    <referencedTypeMoniker Id="4c13560b-accc-4537-a466-aff55cd8e227" LastKnownName="Master" />
                  </type_NamedElement>
                </parameter>
              </operationHasOwnedParameters>
              <operationHasOwnedParameters>
                <parameter Id="56d86a86-bc2e-4723-8cbd-6102433d59e7" name="masterCat" direction="In" isUnique="false">
                  <elementDefinition Id="af993d55-71ae-497a-8aa6-a913cf427687" />
                  <type_NamedElement>
                    <referencedTypeMoniker Id="6c593322-0955-41a8-b52b-79af32acfbe4" LastKnownName="Category" />
                  </type_NamedElement>
                </parameter>
              </operationHasOwnedParameters>
              <operationHasOwnedParameters>
                <parameter Id="911236e1-bef4-45b4-9f31-2b75a88ae27b" name="sortBy" direction="In" isUnique="false">
                  <elementDefinition Id="3cfc9284-df4b-45f6-8db6-392e6e10fa1d" />
                  <type_NamedElement>
                    <referencedTypeMoniker Id="d5ee5cab-70a9-4944-bce8-bc63a90bc18b" LastKnownName="string" />
                  </type_NamedElement>
                </parameter>
              </operationHasOwnedParameters>
              <operationHasOwnedParameters>
                <parameter Id="37fbcfce-909e-47e2-a55e-1d895ef8eea6" name="desk" direction="In" isUnique="false">
                  <elementDefinition Id="6b81d275-ddef-4f1f-b63c-a21849844a66" />
                  <type_NamedElement>
                    <referencedTypeMoniker Id="6a45fed8-1689-4fa9-8e39-f876365db554" LastKnownName="bool" />
                  </type_NamedElement>
                </parameter>
              </operationHasOwnedParameters>
              <operationHasOwnedParameters>
                <parameter Id="c2c2dd31-90fe-4e0e-ae71-d9c0977db80b" name="masterCat" direction="In" isUnique="false">
                  <elementDefinition Id="e2b9ad56-ae44-4ad7-ad1f-f391e987de46" />
                  <type_NamedElement>
                    <referencedTypeMoniker Id="6c593322-0955-41a8-b52b-79af32acfbe4" LastKnownName="Category" />
                  </type_NamedElement>
                </parameter>
              </operationHasOwnedParameters>
              <operationHasOwnedParameters>
                <parameter Id="975caee2-d684-4ae3-a7e6-b116582d6dd2" name="count" direction="In" isUnique="false">
                  <elementDefinition Id="2fcce7ed-9e03-45c0-9066-d4f1af49bdee" />
                  <type_NamedElement>
                    <referencedTypeMoniker Id="2f44e82c-bed6-4a5e-86eb-47ad3618f426" LastKnownName="int" />
                  </type_NamedElement>
                </parameter>
              </operationHasOwnedParameters>
              <operationHasOwnedParameters>
                <parameter Id="3cc69b29-84b6-4805-bf6c-9e085b272b39" name="page" direction="In" isUnique="false">
                  <elementDefinition Id="fc92e907-e449-48c2-be66-46e7de1931f0" />
                  <type_NamedElement>
                    <referencedTypeMoniker Id="de578a74-cb65-4d29-833c-4c0b903c29db" LastKnownName="int" />
                  </type_NamedElement>
                </parameter>
              </operationHasOwnedParameters>
            </ownedParameters>
          </operation>
          <operation Id="8018ffad-c37f-4338-8498-062a16a905c2" name="GetById" isLeaf="false" isStatic="true" isAbstract="false" concurrency="Sequential" isQuery="false">
            <elementDefinition Id="881666db-0a3c-4b44-b41f-0f8c2a42562c" />
            <ownedParameters>
              <operationHasOwnedParameters>
                <parameter Id="1112c425-a9c0-4a3f-9f1f-c24c7e34ab0d" name="Int" direction="In" isUnique="false">
                  <elementDefinition Id="827f0007-49e0-454c-8595-cb0883961e8c" />
                </parameter>
              </operationHasOwnedParameters>
              <operationHasOwnedParameters>
                <parameter Id="5d568d21-24e9-45e7-87f9-cbc60393ecd1" direction="Return" isUnique="false">
                  <elementDefinition Id="e2eed121-956c-46e0-af15-0d92f9772810" />
                  <type_NamedElement>
                    <referencedTypeMoniker Id="4c13560b-accc-4537-a466-aff55cd8e227" LastKnownName="Master" />
                  </type_NamedElement>
                </parameter>
              </operationHasOwnedParameters>
            </ownedParameters>
          </operation>
        </ownedOperationsInternal>
      </class>
    </logicalClassDesignerModelHasTypes>
    <packageHasNamedElement>
      <referencedType Id="3ef2da5a-6889-4914-aec7-a587bd38e5b3" name="List&lt;Manager&gt;" isAbstract="false" isLeaf="false" cachedFullName="List&lt;Manager&gt;">
        <elementDefinition Id="649b9405-e3a0-4a95-b9f2-38981481fb3a" />
      </referencedType>
    </packageHasNamedElement>
    <packageHasNamedElement>
      <referencedType Id="02281085-892e-4238-8ec9-351db9e89291" name="string" isAbstract="false" isLeaf="false" cachedFullName="string">
        <elementDefinition Id="74cafbae-7254-4f6c-9322-6709f1fee30e" />
      </referencedType>
    </packageHasNamedElement>
    <packageHasNamedElement>
      <referencedType Id="3197a905-f3d1-429b-9439-232107ae2988" name="int" isAbstract="false" isLeaf="false" cachedFullName="int">
        <elementDefinition Id="f984419c-cfc8-4466-a4ac-951b45074e3f" />
      </referencedType>
    </packageHasNamedElement>
    <packageHasNamedElement>
      <referencedType Id="d84fc5b8-0dd0-4a22-baae-8393419aed4a" name="int" isAbstract="false" isLeaf="false" cachedFullName="int">
        <elementDefinition Id="f984419c-cfc8-4466-a4ac-951b45074e3f" />
      </referencedType>
    </packageHasNamedElement>
    <logicalClassDesignerModelHasTypes>
      <class Id="5cdfcbc2-185b-4510-bfb4-454697d52c22" name="CategoriesList {static}" isAbstract="false" isLeaf="false" isActiveClass="false">
        <elementDefinition Id="b9adb182-8351-44d3-9ae0-756cf87eb148" />
        <targetEnds>
          <association Id="4ffc21f0-afdb-4b9c-8f49-375f348fd7e3" isDerived="false" sourceEndRoleName="CategorieList {static}" targetEndRoleName="Categorie" isLeaf="false" isAbstract="false">
            <classMoniker Id="ecb68bbe-7ceb-4436-a662-49d34c98b121" LastKnownName="Category" />
            <relationshipOwnedElementsInternal>
              <associationHasOwnedEnds>
                <memberEnd Id="83f4d45d-f94a-4cee-a4a8-ae227ff42ad1" name="CategorieList {static}" isLeaf="false" isStatic="false" isReadOnly="false" isDerived="false" isDerivedUnion="false" aggregation="Shared" isComposite="false" isNavigableOwned="false">
                  <elementDefinition Id="cc498ecd-aa1d-4bc0-b2d3-5284e36914b4" />
                </memberEnd>
              </associationHasOwnedEnds>
              <associationHasOwnedEnds>
                <memberEnd Id="d122f395-b2ae-4ee3-8e2a-9d78a694d879" name="Categorie" isLeaf="false" isStatic="false" isReadOnly="false" isDerived="false" isDerivedUnion="false" aggregation="None" isComposite="false">
                  <lowerValueInternal>
                    <literalString Id="331197cd-1673-4539-99a2-6859a3b85eb5" name="Lower" value="1">
                      <elementDefinition Id="a913c162-25e8-4d09-9946-43ef5e8ed531" />
                    </literalString>
                  </lowerValueInternal>
                  <upperValueInternal>
                    <literalString Id="7945fb09-3352-48f2-876a-f0775d592a68" name="Upper" value="*">
                      <elementDefinition Id="60d258a3-6886-4691-8310-0e2a1574371e" />
                    </literalString>
                  </upperValueInternal>
                  <elementDefinition Id="d16c6583-d47c-4980-8051-7ddb1b97858e" />
                </memberEnd>
              </associationHasOwnedEnds>
            </relationshipOwnedElementsInternal>
            <elementDefinition Id="2933dc0e-dcd5-4541-91fb-e714789ee87c" />
          </association>
        </targetEnds>
        <ownedOperationsInternal>
          <operation Id="9387b537-f56a-473c-b9ca-c692cda36a75" name="GetCategories" isLeaf="false" isStatic="true" isAbstract="false" concurrency="Sequential" isQuery="false">
            <elementDefinition Id="1b87e13e-aa30-4f23-ada3-092984ed60cd" />
            <ownedParameters>
              <operationHasOwnedParameters>
                <parameter Id="2d56aa47-db37-4d95-8303-3ed9998d3fe5" direction="Return" isUnique="false">
                  <elementDefinition Id="4042323b-75bc-4bc6-a375-553cb73dc597" />
                  <type_NamedElement>
                    <referencedTypeMoniker Id="d196a296-ba5f-447c-b890-b886fcfbc7a4" LastKnownName="List&lt;Category&gt;" />
                  </type_NamedElement>
                </parameter>
              </operationHasOwnedParameters>
              <operationHasOwnedParameters>
                <parameter Id="8c1a5da7-e7be-4671-a005-b00d89907a8a" name="filterA" direction="In" isUnique="false">
                  <elementDefinition Id="93a12017-ef8c-4703-ba4d-b85896cde7a8" />
                  <type_NamedElement>
                    <referencedTypeMoniker Id="6c593322-0955-41a8-b52b-79af32acfbe4" LastKnownName="Category" />
                  </type_NamedElement>
                </parameter>
              </operationHasOwnedParameters>
              <operationHasOwnedParameters>
                <parameter Id="4781a28e-c4c4-4d7b-bcae-5c9dd137683d" name="sortBy" direction="In" isUnique="false">
                  <elementDefinition Id="698550d6-0567-4502-b957-af239e07701c" />
                  <type_NamedElement>
                    <referencedTypeMoniker Id="02281085-892e-4238-8ec9-351db9e89291" LastKnownName="string" />
                  </type_NamedElement>
                </parameter>
              </operationHasOwnedParameters>
              <operationHasOwnedParameters>
                <parameter Id="d482d317-3084-466d-b807-85be76030641" name="desk" direction="In" isUnique="false">
                  <elementDefinition Id="a99d8231-eb54-4aa8-81ca-dc3b9edfff4c" />
                  <type_NamedElement>
                    <referencedTypeMoniker Id="6a45fed8-1689-4fa9-8e39-f876365db554" LastKnownName="bool" />
                  </type_NamedElement>
                </parameter>
              </operationHasOwnedParameters>
              <operationHasOwnedParameters>
                <parameter Id="4fa84515-45b7-464d-a81b-b0042838c936" name="count" direction="In" isUnique="false">
                  <elementDefinition Id="3f1dd5a0-54c6-46d3-ace7-a9d267dc0783" />
                  <type_NamedElement>
                    <referencedTypeMoniker Id="3197a905-f3d1-429b-9439-232107ae2988" LastKnownName="int" />
                  </type_NamedElement>
                </parameter>
              </operationHasOwnedParameters>
              <operationHasOwnedParameters>
                <parameter Id="d8cb131a-9c16-4776-bf37-bab4c65e01d7" name="page" direction="In" isUnique="false">
                  <elementDefinition Id="beee1553-858b-470e-b8a7-395edba27dcb" />
                  <type_NamedElement>
                    <referencedTypeMoniker Id="d84fc5b8-0dd0-4a22-baae-8393419aed4a" LastKnownName="int" />
                  </type_NamedElement>
                </parameter>
              </operationHasOwnedParameters>
            </ownedParameters>
          </operation>
          <operation Id="1935b1c6-a8ea-4661-b0c4-8b326be681cc" name="GetById" isLeaf="false" isStatic="true" isAbstract="false" concurrency="Sequential" isQuery="false">
            <elementDefinition Id="24babc11-59ee-47fd-ada9-f3de6bdca426" />
            <ownedParameters>
              <operationHasOwnedParameters>
                <parameter Id="06e36447-9b53-4592-8af6-f0980984f839" name="Int" direction="In" isUnique="false">
                  <elementDefinition Id="7b066d05-3391-4950-b544-c3e5e2b96d5f" />
                </parameter>
              </operationHasOwnedParameters>
              <operationHasOwnedParameters>
                <parameter Id="025da0b1-37a0-46bd-b0ec-89d52f414f61" direction="Return" isUnique="false">
                  <elementDefinition Id="2ee85e55-e4dc-4b1f-8504-bc5bb22f3bd3" />
                  <type_NamedElement>
                    <referencedTypeMoniker Id="6c593322-0955-41a8-b52b-79af32acfbe4" LastKnownName="Category" />
                  </type_NamedElement>
                </parameter>
              </operationHasOwnedParameters>
            </ownedParameters>
          </operation>
        </ownedOperationsInternal>
      </class>
    </logicalClassDesignerModelHasTypes>
    <packageHasNamedElement>
      <referencedType Id="94cfa6e8-66b1-49b0-b1b6-a565ac2b5d1c" name="string" isAbstract="false" isLeaf="false" cachedFullName="string">
        <elementDefinition Id="74cafbae-7254-4f6c-9322-6709f1fee30e" />
      </referencedType>
    </packageHasNamedElement>
    <packageHasNamedElement>
      <referencedType Id="e3a87429-5d76-4ee0-b15b-e953bea230b4" name="int" isAbstract="false" isLeaf="false" cachedFullName="int">
        <elementDefinition Id="f984419c-cfc8-4466-a4ac-951b45074e3f" />
      </referencedType>
    </packageHasNamedElement>
    <packageHasNamedElement>
      <referencedType Id="1abb54f1-2f5e-46e9-990e-40ab52058541" name="int" isAbstract="false" isLeaf="false" cachedFullName="int">
        <elementDefinition Id="f984419c-cfc8-4466-a4ac-951b45074e3f" />
      </referencedType>
    </packageHasNamedElement>
    <logicalClassDesignerModelHasTypes>
      <class Id="c54ee051-abee-4af8-81fa-e363ef6cc2bb" name="ProductsList {static}" isAbstract="false" isLeaf="false" isActiveClass="false">
        <elementDefinition Id="6cf3a691-7a92-4cfb-8a26-dc029a2b044c" />
        <targetEnds>
          <association Id="dbba61da-2cda-46e5-ab8c-60bb0df6cda4" isDerived="false" sourceEndRoleName="ProductList {static}" targetEndRoleName="Product" isLeaf="false" isAbstract="false">
            <classMoniker Id="9b4b7581-ed32-482e-b87e-80fb21168b7b" LastKnownName="Product" />
            <relationshipOwnedElementsInternal>
              <associationHasOwnedEnds>
                <memberEnd Id="2dc7864c-18e4-4c1b-960d-766e438a8ad4" name="ProductList {static}" isLeaf="false" isStatic="false" isReadOnly="false" isDerived="false" isDerivedUnion="false" aggregation="Shared" isComposite="false" isNavigableOwned="false">
                  <elementDefinition Id="718bb7eb-ea7e-4a22-bfe7-407e4f6f1694" />
                </memberEnd>
              </associationHasOwnedEnds>
              <associationHasOwnedEnds>
                <memberEnd Id="a3ef77b0-b014-45b8-b9f3-44cb7faa9fed" name="Product" isLeaf="false" isStatic="false" isReadOnly="false" isDerived="false" isDerivedUnion="false" aggregation="None" isComposite="false">
                  <lowerValueInternal>
                    <literalString Id="4679a4cd-541d-4417-aa45-a57b0810d66d" name="Lower" value="1">
                      <elementDefinition Id="9b2c5315-b0ff-40ed-9fa3-aa487c4077d7" />
                    </literalString>
                  </lowerValueInternal>
                  <upperValueInternal>
                    <literalString Id="823ac518-dc19-4369-9c14-3b3eedff85d8" name="Upper" value="*">
                      <elementDefinition Id="8d9c169a-9020-481c-aa74-1d10382a3704" />
                    </literalString>
                  </upperValueInternal>
                  <elementDefinition Id="8eb022fc-8fa3-4fa4-9ab0-94ba23565d3e" />
                </memberEnd>
              </associationHasOwnedEnds>
            </relationshipOwnedElementsInternal>
            <elementDefinition Id="56c47075-90e1-4684-b5c8-ef41d1639d9e" />
          </association>
        </targetEnds>
        <ownedOperationsInternal>
          <operation Id="3df84a58-7842-4999-809f-3e2282c5bb65" name="GetProducts" isLeaf="false" isStatic="true" isAbstract="false" concurrency="Sequential" isQuery="false">
            <elementDefinition Id="b8b19d16-4f8e-4ac6-b23d-adfed9354be9" />
            <ownedParameters>
              <operationHasOwnedParameters>
                <parameter Id="27f756c8-b1e9-407a-be66-4dd81917d4c0" direction="Return" isUnique="false">
                  <elementDefinition Id="ec10c604-5759-4737-a964-7f94e9dcfadc" />
                  <type_NamedElement>
                    <referencedTypeMoniker Id="01012423-5178-404b-ab49-6f14b60e4c22" LastKnownName="List&lt;Product&gt;" />
                  </type_NamedElement>
                </parameter>
              </operationHasOwnedParameters>
              <operationHasOwnedParameters>
                <parameter Id="f1a9126f-6ccd-4310-9540-e3454eaccdb6" name="filterA" direction="In" isUnique="false">
                  <elementDefinition Id="326fab26-6796-4cd3-a87f-5184128ed1d0" />
                  <type_NamedElement>
                    <referencedTypeMoniker Id="603e91ec-7198-40f7-a47d-8e53c0e49d75" LastKnownName="Product" />
                  </type_NamedElement>
                </parameter>
              </operationHasOwnedParameters>
              <operationHasOwnedParameters>
                <parameter Id="9a4bf9ba-d4b7-4851-9ece-25e09b9c32ae" name="sortBy" direction="In" isUnique="false">
                  <elementDefinition Id="631a3981-9265-4c48-8f96-cdab37e0060e" />
                  <type_NamedElement>
                    <referencedTypeMoniker Id="94cfa6e8-66b1-49b0-b1b6-a565ac2b5d1c" LastKnownName="string" />
                  </type_NamedElement>
                </parameter>
              </operationHasOwnedParameters>
              <operationHasOwnedParameters>
                <parameter Id="eefd458d-ab4f-45df-b982-cb2c36098f73" name="desk" direction="In" isUnique="false">
                  <elementDefinition Id="7e6cc5de-d957-4a35-a338-030e2117e283" />
                  <type_NamedElement>
                    <referencedTypeMoniker Id="6a45fed8-1689-4fa9-8e39-f876365db554" LastKnownName="bool" />
                  </type_NamedElement>
                </parameter>
              </operationHasOwnedParameters>
              <operationHasOwnedParameters>
                <parameter Id="d8ec48f7-a47d-4c43-aea0-26e7d31bf485" name="count" direction="In" isUnique="false">
                  <elementDefinition Id="b071f619-9f55-4e50-ac85-10c5ef625a24" />
                  <type_NamedElement>
                    <referencedTypeMoniker Id="e3a87429-5d76-4ee0-b15b-e953bea230b4" LastKnownName="int" />
                  </type_NamedElement>
                </parameter>
              </operationHasOwnedParameters>
              <operationHasOwnedParameters>
                <parameter Id="5a5c3421-aafd-4ac4-99cd-2cca93db8c97" name="page" direction="In" isUnique="false">
                  <elementDefinition Id="cdcf059e-e8f9-4f8d-982e-6d08d0078591" />
                  <type_NamedElement>
                    <referencedTypeMoniker Id="1abb54f1-2f5e-46e9-990e-40ab52058541" LastKnownName="int" />
                  </type_NamedElement>
                </parameter>
              </operationHasOwnedParameters>
            </ownedParameters>
          </operation>
          <operation Id="c9269c4e-617e-42fd-87b5-e82cc5f1e89c" name="GetById" isLeaf="false" isStatic="true" isAbstract="false" concurrency="Sequential" isQuery="false">
            <elementDefinition Id="5e900863-5c2e-4982-88c0-abfa46aae4cf" />
            <ownedParameters>
              <operationHasOwnedParameters>
                <parameter Id="ebfa06b7-cac1-4b53-87e2-38b6c2e96f74" name="Int" direction="In" isUnique="false">
                  <elementDefinition Id="1787c701-5d6c-4abd-8b50-f00c960f9170" />
                </parameter>
              </operationHasOwnedParameters>
              <operationHasOwnedParameters>
                <parameter Id="2fc953ac-f1bf-4b72-9184-e6532cc045fc" direction="Return" isUnique="false">
                  <elementDefinition Id="0d4ec6d9-dcc2-4b09-a12c-598d6356b915" />
                  <type_NamedElement>
                    <referencedTypeMoniker Id="603e91ec-7198-40f7-a47d-8e53c0e49d75" LastKnownName="Product" />
                  </type_NamedElement>
                </parameter>
              </operationHasOwnedParameters>
            </ownedParameters>
          </operation>
        </ownedOperationsInternal>
      </class>
    </logicalClassDesignerModelHasTypes>
    <packageHasNamedElement>
      <referencedType Id="01012423-5178-404b-ab49-6f14b60e4c22" name="List&lt;Product&gt;" isAbstract="false" isLeaf="false" cachedFullName="List&lt;Product&gt;">
        <elementDefinition Id="77102f2d-5b3e-46cc-aabe-28cf43ee5b37" />
      </referencedType>
    </packageHasNamedElement>
    <packageHasNamedElement>
      <referencedType Id="ef262fd8-80df-43d3-88fc-480ac5b08a13" name="string" isAbstract="false" isLeaf="false" cachedFullName="string">
        <elementDefinition Id="74cafbae-7254-4f6c-9322-6709f1fee30e" />
      </referencedType>
    </packageHasNamedElement>
    <packageHasNamedElement>
      <referencedType Id="7147f99b-1fc7-4dca-8caf-ce3d1ae6c1b7" name="int" isAbstract="false" isLeaf="false" cachedFullName="int">
        <elementDefinition Id="f984419c-cfc8-4466-a4ac-951b45074e3f" />
      </referencedType>
    </packageHasNamedElement>
    <packageHasNamedElement>
      <referencedType Id="7effdb76-1ad6-425b-a43f-c014c34514cc" name="int" isAbstract="false" isLeaf="false" cachedFullName="int">
        <elementDefinition Id="f984419c-cfc8-4466-a4ac-951b45074e3f" />
      </referencedType>
    </packageHasNamedElement>
    <logicalClassDesignerModelHasTypes>
      <class Id="aa308219-6410-4ecf-ad89-4d296a29b152" name="ServicesList {static}" isAbstract="false" isLeaf="false" isActiveClass="false">
        <elementDefinition Id="848948ff-b363-4722-a834-eb53a0e934c7" />
        <targetEnds>
          <association Id="ce435e82-a940-4dc9-8bfb-116fec99b2f0" isDerived="false" sourceEndRoleName="ServicesList {static}" targetEndRoleName="Service" isLeaf="false" isAbstract="false">
            <classMoniker Id="60a4334c-dbe6-43a7-b0f6-19e3f89831ed" LastKnownName="Service" />
            <relationshipOwnedElementsInternal>
              <associationHasOwnedEnds>
                <memberEnd Id="909917fb-7044-4aea-96a4-cb04ab0cc3f3" name="ServicesList {static}" isLeaf="false" isStatic="false" isReadOnly="false" isDerived="false" isDerivedUnion="false" aggregation="Shared" isComposite="false" isNavigableOwned="false">
                  <elementDefinition Id="c7ce28b4-3069-43a3-925b-b1e7c6e6fd1e" />
                </memberEnd>
              </associationHasOwnedEnds>
              <associationHasOwnedEnds>
                <memberEnd Id="8b377133-b549-4a7f-b738-9a17992e2df2" name="Service" isLeaf="false" isStatic="false" isReadOnly="false" isDerived="false" isDerivedUnion="false" aggregation="None" isComposite="false">
                  <lowerValueInternal>
                    <literalString Id="bd988037-3d06-4812-92c5-069fc7c1f8ec" name="Lower" value="1">
                      <elementDefinition Id="6c458fe5-97bd-455f-bcd1-bccbce5316fd" />
                    </literalString>
                  </lowerValueInternal>
                  <upperValueInternal>
                    <literalString Id="626ac45b-ccbf-4443-8332-336a2b64af55" name="Upper" value="*">
                      <elementDefinition Id="8fe27249-d74b-4ca1-9cd8-69ea8d4a8262" />
                    </literalString>
                  </upperValueInternal>
                  <elementDefinition Id="d5910a39-eaa3-461b-ab0b-7ad414128fd3" />
                </memberEnd>
              </associationHasOwnedEnds>
            </relationshipOwnedElementsInternal>
            <elementDefinition Id="57d532b6-6d56-4291-be81-2ba37c0d27fc" />
          </association>
        </targetEnds>
        <ownedOperationsInternal>
          <operation Id="167fe676-0c99-491c-b5f4-25059f12d2ff" name="GetServices" isLeaf="false" isStatic="true" isAbstract="false" concurrency="Sequential" isQuery="false">
            <elementDefinition Id="5d01d988-6725-4e33-a71d-a36cc130a74d" />
            <ownedParameters>
              <operationHasOwnedParameters>
                <parameter Id="2afa863c-6edd-45d2-9574-cbee2f9f2792" direction="Return" isUnique="false">
                  <elementDefinition Id="a842ead8-9250-4791-96eb-0e7503cee537" />
                  <type_NamedElement>
                    <referencedTypeMoniker Id="1e420cc7-7f2d-47cc-88d5-5aad23d5e842" LastKnownName="List&lt;Service&gt;" />
                  </type_NamedElement>
                </parameter>
              </operationHasOwnedParameters>
              <operationHasOwnedParameters>
                <parameter Id="d503235e-401e-4793-bcd0-f6da9bf313f2" name="filterA" direction="In" isUnique="false">
                  <elementDefinition Id="f85d2eaa-f208-4f3e-b466-b03297a29073" />
                  <type_NamedElement>
                    <referencedTypeMoniker Id="9366a8a0-2c9f-4aeb-81b2-7a52156b3689" LastKnownName="Service" />
                  </type_NamedElement>
                </parameter>
              </operationHasOwnedParameters>
              <operationHasOwnedParameters>
                <parameter Id="706cc980-a59b-4ae0-81c0-bf311c667ac0" name="filterB" direction="In" isUnique="false">
                  <elementDefinition Id="0de62c70-985c-4f59-860a-2c5faadb7919" />
                  <type_NamedElement>
                    <referencedTypeMoniker Id="9366a8a0-2c9f-4aeb-81b2-7a52156b3689" LastKnownName="Service" />
                  </type_NamedElement>
                </parameter>
              </operationHasOwnedParameters>
              <operationHasOwnedParameters>
                <parameter Id="14e17fb2-244c-45e8-a12e-aa5a06f241a3" name="withParentsServices" direction="In" isUnique="false">
                  <elementDefinition Id="1ab33ab6-55ad-45aa-a9ad-7c96850636f9" />
                  <type_NamedElement>
                    <referencedTypeMoniker Id="6a45fed8-1689-4fa9-8e39-f876365db554" LastKnownName="bool" />
                  </type_NamedElement>
                </parameter>
              </operationHasOwnedParameters>
              <operationHasOwnedParameters>
                <parameter Id="0d33a124-8620-4a89-af49-7346cee17c15" name="sortBy" direction="In" isUnique="false">
                  <elementDefinition Id="3d317d34-4a6b-4445-8481-cae70445e4af" />
                  <type_NamedElement>
                    <referencedTypeMoniker Id="ef262fd8-80df-43d3-88fc-480ac5b08a13" LastKnownName="string" />
                  </type_NamedElement>
                </parameter>
              </operationHasOwnedParameters>
              <operationHasOwnedParameters>
                <parameter Id="6a9f7c08-1524-4532-9e8d-3c1b3f364e56" name="desk" direction="In" isUnique="false">
                  <elementDefinition Id="4b2f0558-076b-4373-81d1-938db8c165f5" />
                  <type_NamedElement>
                    <referencedTypeMoniker Id="6a45fed8-1689-4fa9-8e39-f876365db554" LastKnownName="bool" />
                  </type_NamedElement>
                </parameter>
              </operationHasOwnedParameters>
              <operationHasOwnedParameters>
                <parameter Id="15e83f0c-ddb9-40f3-ba60-31a68ef5da63" name="count" direction="In" isUnique="false">
                  <elementDefinition Id="9acf5aba-c8e5-42f2-ae33-c887278d3f6a" />
                  <type_NamedElement>
                    <referencedTypeMoniker Id="7147f99b-1fc7-4dca-8caf-ce3d1ae6c1b7" LastKnownName="int" />
                  </type_NamedElement>
                </parameter>
              </operationHasOwnedParameters>
              <operationHasOwnedParameters>
                <parameter Id="f494f6d0-ee85-4d06-8665-9aa5ff408c38" name="page" direction="In" isUnique="false">
                  <elementDefinition Id="54c61da5-c378-4e92-8ea6-5ae0e115b00e" />
                  <type_NamedElement>
                    <referencedTypeMoniker Id="7effdb76-1ad6-425b-a43f-c014c34514cc" LastKnownName="int" />
                  </type_NamedElement>
                </parameter>
              </operationHasOwnedParameters>
            </ownedParameters>
          </operation>
          <operation Id="63a82c28-e320-4445-8900-d56424b71d9e" name="GetById" isLeaf="false" isStatic="true" isAbstract="false" concurrency="Sequential" isQuery="false">
            <elementDefinition Id="2dabac30-14a1-4731-a5be-5149deeabb44" />
            <ownedParameters>
              <operationHasOwnedParameters>
                <parameter Id="d4cd5759-c8b9-46f8-ae46-ccb7b5d79e06" name="Int" direction="In" isUnique="false">
                  <elementDefinition Id="a8b2d885-1293-4c56-a4ee-27c8b2db1c01" />
                </parameter>
              </operationHasOwnedParameters>
              <operationHasOwnedParameters>
                <parameter Id="d61267fb-982d-4fee-818c-29377c5cd915" direction="Return" isUnique="false">
                  <elementDefinition Id="6356d5a2-2209-48ee-9940-91220f432223" />
                  <type_NamedElement>
                    <referencedTypeMoniker Id="9366a8a0-2c9f-4aeb-81b2-7a52156b3689" LastKnownName="Service" />
                  </type_NamedElement>
                </parameter>
              </operationHasOwnedParameters>
            </ownedParameters>
          </operation>
        </ownedOperationsInternal>
      </class>
    </logicalClassDesignerModelHasTypes>
    <packageHasNamedElement>
      <referencedType Id="9366a8a0-2c9f-4aeb-81b2-7a52156b3689" name="Service" isAbstract="false" isLeaf="false" cachedFullName="CompServiceClassDiagram::Service">
        <elementDefinition Id="b0c4b702-5e5a-4e3c-8cd4-918150c7b380" />
      </referencedType>
    </packageHasNamedElement>
    <packageHasNamedElement>
      <referencedType Id="96762167-dba8-4e84-a426-d4426c479168" name="Order" isAbstract="false" isLeaf="false" cachedFullName="CompServiceClassDiagram::Order">
        <elementDefinition Id="4256f795-28db-49f0-8022-8f48d9c63bbe" />
      </referencedType>
    </packageHasNamedElement>
    <packageHasNamedElement>
      <referencedType Id="864aba33-2933-4423-b0d3-30d0d90d8797" name="string" isAbstract="false" isLeaf="false" cachedFullName="string">
        <elementDefinition Id="74cafbae-7254-4f6c-9322-6709f1fee30e" />
      </referencedType>
    </packageHasNamedElement>
    <packageHasNamedElement>
      <referencedType Id="c51d1bd1-b814-4529-bc25-f1f4552acc8a" name="string" isAbstract="false" isLeaf="false" cachedFullName="string">
        <elementDefinition Id="74cafbae-7254-4f6c-9322-6709f1fee30e" />
      </referencedType>
    </packageHasNamedElement>
    <packageHasNamedElement>
      <referencedType Id="735a0165-e410-491f-833c-b71c085ee4d9" name="int" isAbstract="false" isLeaf="false" cachedFullName="int">
        <elementDefinition Id="f984419c-cfc8-4466-a4ac-951b45074e3f" />
      </referencedType>
    </packageHasNamedElement>
    <packageHasNamedElement>
      <referencedType Id="eefe1f55-3f3d-4f64-933d-26674c38ee28" name="int" isAbstract="false" isLeaf="false" cachedFullName="int">
        <elementDefinition Id="f984419c-cfc8-4466-a4ac-951b45074e3f" />
      </referencedType>
    </packageHasNamedElement>
    <logicalClassDesignerModelHasTypes>
      <class Id="a7cd746b-a735-4980-95de-bddd08b3f555" name="WorkshopsList {static}" isAbstract="false" isLeaf="false" isActiveClass="false">
        <elementDefinition Id="8e80f472-42a2-489c-b4bf-ab10133b3425" />
        <targetEnds>
          <association Id="a6397536-56a0-433d-80e0-a0d9a30d2806" isDerived="false" sourceEndRoleName="WorkshopsList {static}" targetEndRoleName="Workshop" isLeaf="false" isAbstract="false">
            <classMoniker Id="cd276153-9c6d-4ebc-b0d1-a6e2838d7c37" LastKnownName="Workshop" />
            <relationshipOwnedElementsInternal>
              <associationHasOwnedEnds>
                <memberEnd Id="67a64110-5fb3-433b-bd2e-aba2a8d051dd" name="WorkshopsList {static}" isLeaf="false" isStatic="false" isReadOnly="false" isDerived="false" isDerivedUnion="false" aggregation="Shared" isComposite="false" isNavigableOwned="false">
                  <elementDefinition Id="55366a64-fdf5-4eda-ac33-10447bcbf41a" />
                </memberEnd>
              </associationHasOwnedEnds>
              <associationHasOwnedEnds>
                <memberEnd Id="cc5118eb-159f-40af-b71e-aabeedca915a" name="Workshop" isLeaf="false" isStatic="false" isReadOnly="false" isDerived="false" isDerivedUnion="false" aggregation="None" isComposite="false">
                  <lowerValueInternal>
                    <literalString Id="123be595-275b-4293-92e4-8c4a7f3756b7" name="Lower" value="1">
                      <elementDefinition Id="c12b2134-65bc-4ce6-bba2-fc77f7573a15" />
                    </literalString>
                  </lowerValueInternal>
                  <upperValueInternal>
                    <literalString Id="4b1c014b-0fd3-44e9-8254-51e01c76261c" name="Upper" value="*">
                      <elementDefinition Id="7d03ad3f-c13f-4b14-ba32-40521ed880a1" />
                    </literalString>
                  </upperValueInternal>
                  <elementDefinition Id="d25f101a-6deb-46a0-b910-b7341ee0c7ae" />
                </memberEnd>
              </associationHasOwnedEnds>
            </relationshipOwnedElementsInternal>
            <elementDefinition Id="c49b9235-0ab0-4c29-9cfb-4fee1bcb1d31" />
          </association>
        </targetEnds>
        <ownedOperationsInternal>
          <operation Id="e1df5381-4f76-4c9b-afee-1e59b07b8528" name="GetWorkshops" isLeaf="false" isStatic="true" isAbstract="false" concurrency="Sequential" isQuery="false">
            <elementDefinition Id="4b91ea2c-4e6d-4fc8-a39f-fe5ccd922d95" />
            <ownedParameters>
              <operationHasOwnedParameters>
                <parameter Id="e1962907-cdf4-422c-a858-bf6ae97926fa" direction="Return" isUnique="false">
                  <elementDefinition Id="e8d43384-943d-459a-a2b2-9a0934e43998" />
                  <type_NamedElement>
                    <referencedTypeMoniker Id="8220a0d9-347c-47ac-945e-e7c6153d9dd0" LastKnownName="List&lt;Workshop&gt;" />
                  </type_NamedElement>
                </parameter>
              </operationHasOwnedParameters>
              <operationHasOwnedParameters>
                <parameter Id="ab20ec5b-e525-4e33-ad66-68e307e27e12" name="filterA" direction="In" isUnique="false">
                  <elementDefinition Id="c0083188-5c9d-4afb-9333-5e7824ae2afd" />
                  <type_NamedElement>
                    <referencedTypeMoniker Id="f4c65483-48fa-48c6-b1ba-774306746da9" LastKnownName="Workshop" />
                  </type_NamedElement>
                </parameter>
              </operationHasOwnedParameters>
              <operationHasOwnedParameters>
                <parameter Id="2fb55862-4480-4eb2-81b2-081a739e8500" name="sorting" direction="In" isUnique="false">
                  <elementDefinition Id="94e80860-98ac-42ad-9a8f-cb54d8219a39" />
                  <type_NamedElement>
                    <referencedTypeMoniker Id="864aba33-2933-4423-b0d3-30d0d90d8797" LastKnownName="string" />
                  </type_NamedElement>
                </parameter>
              </operationHasOwnedParameters>
              <operationHasOwnedParameters>
                <parameter Id="f648f3a4-ce35-4a8d-a117-52a26e87c6c1" name="AskOrDesk" direction="In" isUnique="false">
                  <elementDefinition Id="335e999a-070f-4bab-af74-c00f16de416d" />
                  <type_NamedElement>
                    <referencedTypeMoniker Id="c51d1bd1-b814-4529-bc25-f1f4552acc8a" LastKnownName="string" />
                  </type_NamedElement>
                </parameter>
              </operationHasOwnedParameters>
              <operationHasOwnedParameters>
                <parameter Id="35a65243-bc77-4b82-9a34-45bc57db3231" name="count" direction="In" isUnique="false">
                  <elementDefinition Id="b7691a97-53d7-45e8-ab1f-4a59e1f43cd1" />
                  <type_NamedElement>
                    <referencedTypeMoniker Id="735a0165-e410-491f-833c-b71c085ee4d9" LastKnownName="int" />
                  </type_NamedElement>
                </parameter>
              </operationHasOwnedParameters>
              <operationHasOwnedParameters>
                <parameter Id="8e78acb2-dc4e-4cd4-a71d-f68cc4652324" name="page" direction="In" isUnique="false">
                  <elementDefinition Id="b5a02648-8656-40bf-81e8-def58f14458f" />
                  <type_NamedElement>
                    <referencedTypeMoniker Id="eefe1f55-3f3d-4f64-933d-26674c38ee28" LastKnownName="int" />
                  </type_NamedElement>
                </parameter>
              </operationHasOwnedParameters>
            </ownedParameters>
          </operation>
          <operation Id="eea9bf07-a4db-4799-8208-1d4bbf85ae9b" name="GetById" isLeaf="false" isStatic="true" isAbstract="false" concurrency="Sequential" isQuery="false">
            <elementDefinition Id="10f3a229-1cc8-4ed4-871e-b6abfdb99b84" />
            <ownedParameters>
              <operationHasOwnedParameters>
                <parameter Id="9c9a6360-21ec-4abd-94d1-1d968ed32cfa" name="Int" direction="In" isUnique="false">
                  <elementDefinition Id="64382709-f83d-4095-95ed-b720b31e714e" />
                </parameter>
              </operationHasOwnedParameters>
              <operationHasOwnedParameters>
                <parameter Id="4515cdc3-5501-4e3e-b0ac-d321a27b34ae" direction="Return" isUnique="false">
                  <elementDefinition Id="f90b3e5a-956d-4fa1-8df9-5c906bdc5ac1" />
                  <type_NamedElement>
                    <referencedTypeMoniker Id="f4c65483-48fa-48c6-b1ba-774306746da9" LastKnownName="Workshop" />
                  </type_NamedElement>
                </parameter>
              </operationHasOwnedParameters>
            </ownedParameters>
          </operation>
        </ownedOperationsInternal>
      </class>
    </logicalClassDesignerModelHasTypes>
    <packageHasNamedElement>
      <referencedType Id="8220a0d9-347c-47ac-945e-e7c6153d9dd0" name="List&lt;Workshop&gt;" isAbstract="false" isLeaf="false" cachedFullName="List&lt;Workshop&gt;">
        <elementDefinition Id="54b607b9-2cca-4a6e-89bf-a9c26e342fbd" />
      </referencedType>
    </packageHasNamedElement>
    <logicalClassDesignerModelHasTypes>
      <enumeration Id="3f4ac811-cadd-40c5-8b1d-43bbebcbdbdc" name="OrderStatus" isAbstract="false" isLeaf="false">
        <elementDefinition Id="7cb9ba58-700a-4b25-add8-bd121d1e03ea" />
        <suppliersInternal>
          <dependency Id="4fa10f80-e93d-4e7f-861d-5cae3df43dde">
            <classMoniker Id="04d085bd-93e1-404d-b8cd-d5e6b85bd1ed" LastKnownName="Order" />
            <elementDefinition Id="ff7970ef-a914-4fa4-961f-c8d02a9c2874" />
          </dependency>
        </suppliersInternal>
        <ownedLiterals>
          <enumerationLiteral Id="5b888334-bb76-4351-9e5e-a116396ca804" name="Ready to issue">
            <elementDefinition Id="79e11c71-8830-4493-b499-3da035cb5f70" />
          </enumerationLiteral>
          <enumerationLiteral Id="3fc12050-939e-4aab-acaf-009a362ae18b" name="Finished">
            <elementDefinition Id="aaf6cece-c285-4253-bfb6-13de763ec837" />
          </enumerationLiteral>
          <enumerationLiteral Id="136c6e15-9aea-4387-bf21-0d35337f0f71" name="Canceled">
            <elementDefinition Id="f8ed2eb7-1f02-4df9-89c9-3a332a473a00" />
          </enumerationLiteral>
          <enumerationLiteral Id="c661f6d2-f93e-4ac5-b7b3-b543c20e3711" name="Waiting for diagnostic">
            <elementDefinition Id="4afa427c-4e68-4255-a81b-62264436427c" />
          </enumerationLiteral>
          <enumerationLiteral Id="3b9b5b6d-bc44-45b7-ae2b-c19edb80b53b" name="Waiting for repairing">
            <elementDefinition Id="778c2596-05d5-493a-907e-45db346bcb1a" />
          </enumerationLiteral>
          <enumerationLiteral Id="71240e92-be40-45c9-92be-37d1e2720d86" name="Waiting for answer">
            <elementDefinition Id="5c761be1-8320-4aa7-a0c5-0568285ebe9f" />
          </enumerationLiteral>
          <enumerationLiteral Id="b781e64e-675b-4a7d-b355-fb22f87ee03c" name="Waiting for prepayment">
            <elementDefinition Id="bce1cc70-a749-4d9d-8bb6-b78332176b7d" />
          </enumerationLiteral>
          <enumerationLiteral Id="c5e6fe3e-ec7a-49a3-9b83-0a3255e710ac" name="Waiting for refund">
            <elementDefinition Id="5969e233-dc4c-4f7f-a3ed-93914c2ba9f8" />
          </enumerationLiteral>
          <enumerationLiteral Id="7688a481-2fa9-44ab-8ffb-b39c7ea27d8e" name="Waiting for spare parts">
            <elementDefinition Id="75b58e76-aa9a-42ee-ac3b-276830048cd2" />
          </enumerationLiteral>
          <enumerationLiteral Id="c0666cb9-b4ea-4670-a249-36fd33665633" name="Waiting for payment">
            <elementDefinition Id="f967931e-dbc5-4cf5-9692-597b1c949562" />
          </enumerationLiteral>
        </ownedLiterals>
      </enumeration>
    </logicalClassDesignerModelHasTypes>
    <packageHasNamedElement>
      <referencedType Id="7bfa11b8-8bde-4368-8759-fc671404c53c" name="OrderStatus" isAbstract="false" isLeaf="false" cachedFullName="CompServiceClassDiagram::OrderStatus">
        <elementDefinition Id="7cb9ba58-700a-4b25-add8-bd121d1e03ea" />
      </referencedType>
    </packageHasNamedElement>
    <packageHasNamedElement>
      <referencedType Id="d0e2218a-5be7-46cf-97a2-091e3a6a80e0" name="decimal" isAbstract="false" isLeaf="false" cachedFullName="decimal">
        <elementDefinition Id="bb3d1d49-bf88-4270-b5ad-3f1901f7c1e5" />
      </referencedType>
    </packageHasNamedElement>
    <packageHasNamedElement>
      <referencedType Id="b3009d99-3060-464b-91db-2d89eac4632b" name="decimal" isAbstract="false" isLeaf="false" cachedFullName="decimal">
        <elementDefinition Id="bb3d1d49-bf88-4270-b5ad-3f1901f7c1e5" />
      </referencedType>
    </packageHasNamedElement>
    <packageHasNamedElement>
      <referencedType Id="b54dbda3-8339-49d3-8866-b7282104c16b" name="decimal" isAbstract="false" isLeaf="false" cachedFullName="decimal">
        <elementDefinition Id="bb3d1d49-bf88-4270-b5ad-3f1901f7c1e5" />
      </referencedType>
    </packageHasNamedElement>
    <packageHasNamedElement>
      <referencedType Id="d196a296-ba5f-447c-b890-b886fcfbc7a4" name="List&lt;Category&gt;" isAbstract="false" isLeaf="false" cachedFullName="List&lt;Category&gt;">
        <elementDefinition Id="a53be48d-027e-40a0-8bed-517f1d0a980c" />
      </referencedType>
    </packageHasNamedElement>
    <packageHasNamedElement>
      <referencedType Id="216ec45d-0959-4ce1-9479-89588bab40bd" name="Category" isAbstract="false" isLeaf="false" cachedFullName="CompServiceClassDiagram::Category">
        <elementDefinition Id="727e2bd1-9ffe-4f58-a321-0a671237657e" />
      </referencedType>
    </packageHasNamedElement>
    <packageHasNamedElement>
      <referencedType Id="2a6dcd0a-0273-4010-921a-49f2fd199f54" name="Category" isAbstract="false" isLeaf="false" cachedFullName="CompServiceClassDiagram::Category">
        <elementDefinition Id="727e2bd1-9ffe-4f58-a321-0a671237657e" />
      </referencedType>
    </packageHasNamedElement>
    <packageHasNamedElement>
      <referencedType Id="8f053d6a-4a26-47f8-9af2-662245598a78" name="bool" isAbstract="false" isLeaf="false" cachedFullName="bool">
        <elementDefinition Id="9b3d5d60-324b-4301-b8f5-3750227e268c" />
      </referencedType>
    </packageHasNamedElement>
    <packageHasNamedElement>
      <referencedType Id="f74590fe-7b39-49d1-9aa0-7d9209443024" name="DateTime" isAbstract="false" isLeaf="false" cachedFullName="DateTime">
        <elementDefinition Id="6f1e3583-6453-46eb-9e38-2685f90d378f" />
      </referencedType>
    </packageHasNamedElement>
    <packageHasNamedElement>
      <referencedType Id="a50b5088-35ce-4516-9bba-64711c467f82" name="DateTime" isAbstract="false" isLeaf="false" cachedFullName="DateTime">
        <elementDefinition Id="6f1e3583-6453-46eb-9e38-2685f90d378f" />
      </referencedType>
    </packageHasNamedElement>
    <packageHasNamedElement>
      <referencedType Id="6b3c41e0-5105-475b-a60d-2186a484e61d" name="DateTime" isAbstract="false" isLeaf="false" cachedFullName="DateTime">
        <elementDefinition Id="6f1e3583-6453-46eb-9e38-2685f90d378f" />
      </referencedType>
    </packageHasNamedElement>
    <logicalClassDesignerModelHasTypes>
      <class Id="571d2f84-3da1-4c3f-a2e4-9b8d443c215c" name="WorkshopTimetable" isAbstract="false" isLeaf="false" isActiveClass="false">
        <elementDefinition Id="279a0b71-1c89-4994-9718-501b4c8b1447" />
        <targetEnds>
          <association Id="7468fd9c-8d2d-4146-aae3-acc1f599b6a9" isDerived="false" sourceEndRoleName="WorkshopTimetable" targetEndRoleName="Workshop" isLeaf="false" isAbstract="false">
            <classMoniker Id="cd276153-9c6d-4ebc-b0d1-a6e2838d7c37" LastKnownName="Workshop" />
            <relationshipOwnedElementsInternal>
              <associationHasOwnedEnds>
                <memberEnd Id="a99fbde9-2512-4e9a-8537-adc2f5af5526" name="WorkshopTimetable" isLeaf="false" isStatic="false" isReadOnly="false" isDerived="false" isDerivedUnion="false" aggregation="Composite" isComposite="false" isNavigableOwned="false">
                  <lowerValueInternal>
                    <literalString Id="70d70f86-b677-4777-b570-ac8d5e47f827" name="Lower" value="1">
                      <elementDefinition Id="b692dce4-f302-47cc-8ca4-544c01ca95c7" />
                    </literalString>
                  </lowerValueInternal>
                  <upperValueInternal>
                    <literalString Id="a180c7ae-f91b-4ce7-92cf-836baae37bb9" name="Upper" value="*">
                      <elementDefinition Id="600b2f50-7f9d-41d6-ae14-123a40fdbad5" />
                    </literalString>
                  </upperValueInternal>
                  <elementDefinition Id="6be61f3d-fda5-445c-a843-12417a066c64" />
                </memberEnd>
              </associationHasOwnedEnds>
              <associationHasOwnedEnds>
                <memberEnd Id="30e83688-b428-44c9-ad87-07c90e0cc438" name="Workshop" isLeaf="false" isStatic="false" isReadOnly="false" isDerived="false" isDerivedUnion="false" aggregation="None" isComposite="true">
                  <elementDefinition Id="efa0e909-6e61-479d-93d3-e179a531c393" />
                </memberEnd>
              </associationHasOwnedEnds>
            </relationshipOwnedElementsInternal>
            <elementDefinition Id="459444b5-5d22-4bf9-8269-844599bfd84b" />
          </association>
        </targetEnds>
        <ownedAttributesInternal>
          <property Id="f7a8dc00-c48e-406f-b55f-48c24d03987c" name="id" isLeaf="false" isStatic="false" isReadOnly="false" isUnique="false" isDerived="false" isDerivedUnion="false" aggregation="None" isComposite="false">
            <elementDefinition Id="25d1f2eb-65e4-4009-b19b-d67c5d924fe7" />
            <type_NamedElement>
              <referencedTypeMoniker Id="82f7932c-0cb2-42de-935f-6430b32cf77f" LastKnownName="Integer" />
            </type_NamedElement>
          </property>
          <property Id="72023496-c388-4765-af0b-09064a3a7e23" name="ValidFrom" isLeaf="false" isStatic="false" isReadOnly="false" isUnique="false" isDerived="false" isDerivedUnion="false" aggregation="None" isComposite="false">
            <elementDefinition Id="eaad615a-1327-401f-8516-bb1978ca3718" />
            <type_NamedElement>
              <referencedTypeMoniker Id="5e95a766-896f-41c7-8951-778ddf708d7a" LastKnownName="DateTime" />
            </type_NamedElement>
          </property>
          <property Id="dca2b288-c7f2-4eb3-8373-d5bcec072123" name="ValidUntil" isLeaf="false" isStatic="false" isReadOnly="false" isUnique="false" isDerived="false" isDerivedUnion="false" aggregation="None" isComposite="false">
            <elementDefinition Id="5a89d9a1-efb3-43fd-8206-aa93996de01d" />
            <type_NamedElement>
              <referencedTypeMoniker Id="5e95a766-896f-41c7-8951-778ddf708d7a" LastKnownName="DateTime" />
            </type_NamedElement>
          </property>
          <property Id="8b1598a3-164c-4f3e-b394-9a6da5c5c60b" name="Closing" isLeaf="false" isStatic="false" isReadOnly="false" isUnique="false" isDerived="false" isDerivedUnion="false" aggregation="None" isComposite="false">
            <elementDefinition Id="4ea5cd15-2259-48ce-8e35-715bc7800199" />
            <type_NamedElement>
              <referencedTypeMoniker Id="18a2239e-dca6-460c-a9db-d2839e4f402a" LastKnownName="DateTime" />
            </type_NamedElement>
          </property>
          <property Id="facfa2ac-0223-43b0-8529-7ca82dada476" name="Opening" isLeaf="false" isStatic="false" isReadOnly="false" isUnique="false" isDerived="false" isDerivedUnion="false" aggregation="None" isComposite="false">
            <elementDefinition Id="7d787098-c9dd-461e-8725-362597f52f45" />
            <type_NamedElement>
              <referencedTypeMoniker Id="66d298c7-0303-47fb-beda-4002f6281207" LastKnownName="DateTime" />
            </type_NamedElement>
          </property>
          <property Id="0c5bd0e7-3a75-4048-9bcd-7ccc4d26ce43" name="Workshop" isLeaf="false" isStatic="false" isReadOnly="false" isUnique="false" isDerived="false" isDerivedUnion="false" aggregation="None" isComposite="false">
            <elementDefinition Id="0ae6f5fe-2390-406f-a90f-fa9817e6db46" />
            <type_NamedElement>
              <referencedTypeMoniker Id="f4c65483-48fa-48c6-b1ba-774306746da9" LastKnownName="Workshop" />
            </type_NamedElement>
          </property>
          <property Id="57e8bd56-6836-4fd0-a814-a56c8383ad30" name="DelTime" isLeaf="false" isStatic="false" isReadOnly="false" isUnique="false" isDerived="false" isDerivedUnion="false" aggregation="None" isComposite="false">
            <elementDefinition Id="25f39ee1-466f-4f0e-8fa5-3c1447842687" />
            <type_NamedElement>
              <referencedTypeMoniker Id="5e95a766-896f-41c7-8951-778ddf708d7a" LastKnownName="DateTime" />
            </type_NamedElement>
          </property>
        </ownedAttributesInternal>
        <ownedOperationsInternal>
          <operation Id="f6328779-05d9-43df-b9b5-1828d5b8801e" name="WorkshopTimetable" isLeaf="false" isStatic="false" isAbstract="false" concurrency="Sequential" isQuery="false">
            <elementDefinition Id="4885385c-766b-4ee3-8080-5d04e6f3a93b" />
            <ownedParameters>
              <operationHasOwnedParameters>
                <parameter Id="ec83e320-9c16-46a0-9a5d-3733d8e89741" direction="Return" isUnique="false">
                  <elementDefinition Id="337e0a7f-7360-4411-8a8b-2623cb3da663" />
                  <type_NamedElement>
                    <referencedTypeMoniker Id="62e1c591-1fc8-4d49-889d-ba3d80faa959" LastKnownName="void" />
                  </type_NamedElement>
                </parameter>
              </operationHasOwnedParameters>
            </ownedParameters>
          </operation>
          <operation Id="046dcde7-cf81-4e53-9dd6-82218e225c9c" name="AddWorkshopTimetable" isLeaf="false" isStatic="false" isAbstract="false" concurrency="Sequential" isQuery="false">
            <elementDefinition Id="a6f47d24-0170-4d1b-80f7-0013725a56a1" />
            <ownedParameters>
              <operationHasOwnedParameters>
                <parameter Id="f20b1868-a825-4eb2-8c2e-408769845510" direction="Return" isUnique="false">
                  <elementDefinition Id="1b1f427a-e3bc-42fe-8a93-1ccc2e30a42a" />
                  <type_NamedElement>
                    <referencedTypeMoniker Id="6a45fed8-1689-4fa9-8e39-f876365db554" LastKnownName="bool" />
                  </type_NamedElement>
                </parameter>
              </operationHasOwnedParameters>
            </ownedParameters>
          </operation>
          <operation Id="8d24c4f4-be91-4200-b7af-ff0c271a90ac" name="DelWorkshopTimetable" isLeaf="false" isStatic="false" isAbstract="false" concurrency="Sequential" isQuery="false">
            <elementDefinition Id="58fb3a64-bfea-4dcf-84ad-c9f772dc0c8f" />
            <ownedParameters>
              <operationHasOwnedParameters>
                <parameter Id="5c81c866-f019-48ac-a224-08e2f0ae5334" direction="Return" isUnique="false">
                  <elementDefinition Id="fcc73a85-5df2-445d-bbef-c4582bd2dd9c" />
                  <type_NamedElement>
                    <referencedTypeMoniker Id="6a45fed8-1689-4fa9-8e39-f876365db554" LastKnownName="bool" />
                  </type_NamedElement>
                </parameter>
              </operationHasOwnedParameters>
            </ownedParameters>
          </operation>
          <operation Id="c58dd2a2-a0e0-4476-8b26-d6c4b3840352" name="EditWorkshopTimetable" isLeaf="false" isStatic="false" isAbstract="false" concurrency="Sequential" isQuery="false">
            <elementDefinition Id="09177cac-c867-4140-853a-f20d4b993b2f" />
            <ownedParameters>
              <operationHasOwnedParameters>
                <parameter Id="c0664d3d-e2aa-4735-a177-37ca3e749b6b" direction="Return" isUnique="false">
                  <elementDefinition Id="42c93e27-e4fa-4270-a6e8-d67204f12935" />
                  <type_NamedElement>
                    <referencedTypeMoniker Id="6a45fed8-1689-4fa9-8e39-f876365db554" LastKnownName="bool" />
                  </type_NamedElement>
                </parameter>
              </operationHasOwnedParameters>
            </ownedParameters>
          </operation>
        </ownedOperationsInternal>
      </class>
    </logicalClassDesignerModelHasTypes>
    <packageHasNamedElement>
      <referencedType Id="66d298c7-0303-47fb-beda-4002f6281207" name="DateTime" isAbstract="false" isLeaf="false" cachedFullName="DateTime">
        <elementDefinition Id="6f1e3583-6453-46eb-9e38-2685f90d378f" />
      </referencedType>
    </packageHasNamedElement>
    <packageHasNamedElement>
      <referencedType Id="18a2239e-dca6-460c-a9db-d2839e4f402a" name="DateTime" isAbstract="false" isLeaf="false" cachedFullName="DateTime">
        <elementDefinition Id="6f1e3583-6453-46eb-9e38-2685f90d378f" />
      </referencedType>
    </packageHasNamedElement>
    <logicalClassDesignerModelHasTypes>
      <class Id="53066004-9395-4113-afdd-9a344a8c03d3" name="EmplyeeTimetable" isAbstract="false" isLeaf="false" isActiveClass="false">
        <elementDefinition Id="7268a3af-922c-4d5b-a474-3c90ebcb4600" />
        <targetEnds>
          <association Id="50fd6f71-07cb-4d29-b93f-6d5bd4d78cf9" isDerived="false" sourceEndRoleName="EmplyeeTimetable" targetEndRoleName="Employee " isLeaf="false" isAbstract="false">
            <classMoniker Id="9e4efbc8-78da-4018-bab1-5d0f33397b70" LastKnownName="Employee {abstract}" />
            <relationshipOwnedElementsInternal>
              <associationHasOwnedEnds>
                <memberEnd Id="54599ba9-4d62-46a0-a67c-abb8202ca9b1" name="EmplyeeTimetable" isLeaf="false" isStatic="false" isReadOnly="false" isDerived="false" isDerivedUnion="false" aggregation="Composite" isComposite="false" isNavigableOwned="false">
                  <lowerValueInternal>
                    <literalString Id="5942be9f-3502-49cb-8059-d730ca473643" name="Lower" value="1">
                      <elementDefinition Id="4c948922-08f6-4b92-8605-f1830df3e5fb" />
                    </literalString>
                  </lowerValueInternal>
                  <upperValueInternal>
                    <literalString Id="f2a5b0dd-fefc-427b-85ac-09c8a4a19acd" name="Upper" value="*">
                      <elementDefinition Id="2ed51318-0d05-41a0-b0ac-8173ef558472" />
                    </literalString>
                  </upperValueInternal>
                  <elementDefinition Id="54ee3ac9-fad3-4c73-84e4-311f4f00fa3f" />
                </memberEnd>
              </associationHasOwnedEnds>
              <associationHasOwnedEnds>
                <memberEnd Id="4013a238-d054-4e6b-904c-e086ec87310a" name="Employee " isLeaf="false" isStatic="false" isReadOnly="false" isDerived="false" isDerivedUnion="false" aggregation="None" isComposite="true">
                  <elementDefinition Id="2b13720f-b177-48ba-b31e-572fdbef7a96" />
                </memberEnd>
              </associationHasOwnedEnds>
            </relationshipOwnedElementsInternal>
            <elementDefinition Id="935d66df-2541-4131-8cd3-3772dad4e8a2" />
          </association>
        </targetEnds>
        <ownedAttributesInternal>
          <property Id="621412ac-24f4-44af-8d28-d4459c7b5bbe" name="id" isLeaf="false" isStatic="false" isReadOnly="false" isUnique="false" isDerived="false" isDerivedUnion="false" aggregation="None" isComposite="false">
            <elementDefinition Id="04f453db-bc49-4243-89d0-c7c90a8cc0bc" />
            <type_NamedElement>
              <referencedTypeMoniker Id="8566a71b-a965-461b-a08d-223bd60ca97c" LastKnownName="Integer" />
            </type_NamedElement>
          </property>
          <property Id="8b0a2f26-2dac-4379-b12f-8bee9e2a4f4e" name="ShiftStart" isLeaf="false" isStatic="false" isReadOnly="false" isUnique="false" isDerived="false" isDerivedUnion="false" aggregation="None" isComposite="false">
            <elementDefinition Id="1ce66e8b-5e03-4d84-acd4-f4a9874e8335" />
            <type_NamedElement>
              <referencedTypeMoniker Id="5e95a766-896f-41c7-8951-778ddf708d7a" LastKnownName="DateTime" />
            </type_NamedElement>
          </property>
          <property Id="8ea98e1b-d8c8-4c07-849c-3fa52d180391" name="ShiftEnd" isLeaf="false" isStatic="false" isReadOnly="false" isUnique="false" isDerived="false" isDerivedUnion="false" aggregation="None" isComposite="false">
            <elementDefinition Id="ce03f443-fc82-4a0a-9f13-e9a079f0eb36" />
            <type_NamedElement>
              <referencedTypeMoniker Id="5e95a766-896f-41c7-8951-778ddf708d7a" LastKnownName="DateTime" />
            </type_NamedElement>
          </property>
          <property Id="8b2a4518-12d8-444d-8f59-865d75328ba3" name="Employee" isLeaf="false" isStatic="false" isReadOnly="false" isUnique="false" isDerived="false" isDerivedUnion="false" aggregation="None" isComposite="false">
            <elementDefinition Id="a4aedbfb-5b60-4b37-b820-f62875bfb4e2" />
            <type_NamedElement>
              <referencedTypeMoniker Id="448d814c-c87b-42ed-9f0f-59cb5e5b0d67" LastKnownName="Employee" />
            </type_NamedElement>
          </property>
          <property Id="b9e2e55e-b802-4c5d-b229-3cfc5810bfda" name="DelTime" isLeaf="false" isStatic="false" isReadOnly="false" isUnique="false" isDerived="false" isDerivedUnion="false" aggregation="None" isComposite="false">
            <elementDefinition Id="195f86a7-c4ea-4f8f-87f9-a48c62945187" />
            <type_NamedElement>
              <referencedTypeMoniker Id="5e95a766-896f-41c7-8951-778ddf708d7a" LastKnownName="DateTime" />
            </type_NamedElement>
          </property>
        </ownedAttributesInternal>
        <ownedOperationsInternal>
          <operation Id="f0489182-7db5-4791-9185-96ce90178477" name="EditTimetable" isLeaf="false" isStatic="false" isAbstract="false" concurrency="Sequential" isQuery="false">
            <elementDefinition Id="3dfcf283-20de-44a2-bb82-1593034f5b87" />
            <ownedParameters>
              <operationHasOwnedParameters>
                <parameter Id="cc2dfa52-7068-4d98-bc70-66be22e650d5" direction="Return" isUnique="false">
                  <elementDefinition Id="f0bb58af-57d6-4b6b-b8a4-9c1f1b50e03a" />
                  <type_NamedElement>
                    <referencedTypeMoniker Id="6a45fed8-1689-4fa9-8e39-f876365db554" LastKnownName="bool" />
                  </type_NamedElement>
                </parameter>
              </operationHasOwnedParameters>
            </ownedParameters>
          </operation>
          <operation Id="d0c418bd-33fa-4c07-9c57-789e8d95b56b" name="AddTimetable" isLeaf="false" isStatic="false" isAbstract="false" concurrency="Sequential" isQuery="false">
            <elementDefinition Id="79223a65-c5f7-414f-9536-dd32df8048e2" />
            <ownedParameters>
              <operationHasOwnedParameters>
                <parameter Id="f75a9431-bfae-4e5d-9905-07889be516d4" direction="Return" isUnique="false">
                  <elementDefinition Id="95e2323c-2b40-49f9-9373-55bea2ff6437" />
                  <type_NamedElement>
                    <referencedTypeMoniker Id="6a45fed8-1689-4fa9-8e39-f876365db554" LastKnownName="bool" />
                  </type_NamedElement>
                </parameter>
              </operationHasOwnedParameters>
            </ownedParameters>
          </operation>
          <operation Id="56f22489-bafb-45b2-aff4-95769446d794" name="DelTimetable" isLeaf="false" isStatic="false" isAbstract="false" concurrency="Sequential" isQuery="false">
            <elementDefinition Id="81c019a0-3d70-463f-bd99-011b9a772d08" />
            <ownedParameters>
              <operationHasOwnedParameters>
                <parameter Id="223bad5d-11bc-4c68-847b-068dbd544aea" direction="Return" isUnique="false">
                  <elementDefinition Id="485e5e7d-2b90-4101-a3eb-9a4fb3c6836d" />
                  <type_NamedElement>
                    <referencedTypeMoniker Id="6a45fed8-1689-4fa9-8e39-f876365db554" LastKnownName="bool" />
                  </type_NamedElement>
                </parameter>
              </operationHasOwnedParameters>
            </ownedParameters>
          </operation>
          <operation Id="4aeae3ed-4170-4efe-9526-c5d84f84fe17" name="EmplyeeTimetable" isLeaf="false" isStatic="false" isAbstract="false" concurrency="Sequential" isQuery="false">
            <elementDefinition Id="0c0d1001-c5ad-4219-a963-af02c981bec6" />
            <ownedParameters>
              <operationHasOwnedParameters>
                <parameter Id="0a4b401f-b955-4cad-84cb-3d1cacad882b" direction="Return" isUnique="false">
                  <elementDefinition Id="42c77c31-c023-4735-9198-bd9259dcf922" />
                  <type_NamedElement>
                    <referencedTypeMoniker Id="62e1c591-1fc8-4d49-889d-ba3d80faa959" LastKnownName="void" />
                  </type_NamedElement>
                </parameter>
              </operationHasOwnedParameters>
            </ownedParameters>
          </operation>
        </ownedOperationsInternal>
      </class>
    </logicalClassDesignerModelHasTypes>
    <packageHasNamedElement>
      <referencedType Id="8566a71b-a965-461b-a08d-223bd60ca97c" name="Integer" isAbstract="false" isLeaf="false" cachedFullName="Integer">
        <elementDefinition Id="220a3521-e091-4221-bae9-3ef9018e845c" />
      </referencedType>
    </packageHasNamedElement>
    <packageHasNamedElement>
      <referencedType Id="82f7932c-0cb2-42de-935f-6430b32cf77f" name="Integer" isAbstract="false" isLeaf="false" cachedFullName="Integer">
        <elementDefinition Id="220a3521-e091-4221-bae9-3ef9018e845c" />
      </referencedType>
    </packageHasNamedElement>
    <packageHasNamedElement>
      <referencedType Id="13b549a6-70aa-477b-94d8-e8ab90df878c" name="Integer" isAbstract="false" isLeaf="false" cachedFullName="Integer">
        <elementDefinition Id="220a3521-e091-4221-bae9-3ef9018e845c" />
      </referencedType>
    </packageHasNamedElement>
    <packageHasNamedElement>
      <referencedType Id="448d814c-c87b-42ed-9f0f-59cb5e5b0d67" name="Employee" isAbstract="false" isLeaf="false" cachedFullName="Employee">
        <elementDefinition Id="252db873-c497-4486-9a3e-93ac38242a9c" />
      </referencedType>
    </packageHasNamedElement>
    <packageHasNamedElement>
      <referencedType Id="71b933ea-7489-4e1c-8c74-7c5423e0afc1" name="EmployeeTimetable" isAbstract="false" isLeaf="false" cachedFullName="EmployeeTimetable">
        <elementDefinition Id="ae5cefd9-dc46-4d9c-9ee4-a46f8d1b6d9c" />
      </referencedType>
    </packageHasNamedElement>
    <packageHasNamedElement>
      <referencedType Id="b226682f-730a-40bb-be1b-9ad80cd255ed" name="List&lt;EmployeeTimetable&gt;" isAbstract="false" isLeaf="false" cachedFullName="List&lt;EmployeeTimetable&gt;">
        <elementDefinition Id="bc611776-b9a6-454b-8b80-4d745704f426" />
      </referencedType>
    </packageHasNamedElement>
    <packageHasNamedElement>
      <referencedType Id="04c69843-b4ee-48ec-984a-fbaa08a042e5" name="WorkshopTimetable" isAbstract="false" isLeaf="false" cachedFullName="CompServiceClassDiagram::WorkshopTimetable">
        <elementDefinition Id="279a0b71-1c89-4994-9718-501b4c8b1447" />
      </referencedType>
    </packageHasNamedElement>
    <packageHasNamedElement>
      <referencedType Id="10bb8f97-f852-412f-8c7d-c81490f9f614" name="List&lt;SparePart&gt;" isAbstract="false" isLeaf="false" cachedFullName="List&lt;SparePart&gt;">
        <elementDefinition Id="8f9305c3-6a36-424a-b84f-561f295fafb2" />
      </referencedType>
    </packageHasNamedElement>
    <logicalClassDesignerModelHasTypes>
      <class Id="54366314-946c-4080-8f16-d8ad82b3c750" name="SpareSpartsList {static}" isAbstract="false" isLeaf="false" isActiveClass="false">
        <elementDefinition Id="6088b966-8011-457a-8daa-73a60926f17a" />
        <targetEnds>
          <association Id="145a0596-c559-4bef-aac3-45764a3da4b1" isDerived="false" sourceEndRoleName="SpareSpartsList {static}" targetEndRoleName="SparePart" isLeaf="false" isAbstract="false">
            <classMoniker Id="eeea4536-adc9-431d-8cb2-7cad87e92193" LastKnownName="SparePart" />
            <relationshipOwnedElementsInternal>
              <associationHasOwnedEnds>
                <memberEnd Id="887fd102-d7f7-4a41-8668-8a51b3fe0d18" name="SpareSpartsList {static}" isLeaf="false" isStatic="false" isReadOnly="false" isDerived="false" isDerivedUnion="false" aggregation="Shared" isComposite="false" isNavigableOwned="false">
                  <elementDefinition Id="091b957a-4b43-4092-8a8b-2911db41b106" />
                </memberEnd>
              </associationHasOwnedEnds>
              <associationHasOwnedEnds>
                <memberEnd Id="b1f565a2-ae2f-44ee-bcea-9ebc40b33cef" name="SparePart" isLeaf="false" isStatic="false" isReadOnly="false" isDerived="false" isDerivedUnion="false" aggregation="None" isComposite="false">
                  <lowerValueInternal>
                    <literalString Id="f970f94e-978e-448e-b5e0-238533b04e87" name="Lower" value="1">
                      <elementDefinition Id="e471c38c-f39a-451e-8527-9495aa0f4ea9" />
                    </literalString>
                  </lowerValueInternal>
                  <upperValueInternal>
                    <literalString Id="90b93df2-58e2-4dee-8a84-9d26390bd75c" name="Upper" value="*">
                      <elementDefinition Id="23a8873c-cb7d-485b-b857-3c98ae146271" />
                    </literalString>
                  </upperValueInternal>
                  <elementDefinition Id="8f54aa4a-ddef-458d-92da-ad4090f4a917" />
                </memberEnd>
              </associationHasOwnedEnds>
            </relationshipOwnedElementsInternal>
            <elementDefinition Id="f49ab8a6-2589-4b09-b7c7-4ca50c36cd74" />
          </association>
        </targetEnds>
        <ownedOperationsInternal>
          <operation Id="57190460-6800-472a-b43a-8443bfbcdd10" name="GetSpareParts" isLeaf="false" isStatic="true" isAbstract="false" concurrency="Sequential" isQuery="false">
            <elementDefinition Id="daf64b33-db1d-4249-a0f0-6e5d44ca688d" />
            <ownedParameters>
              <operationHasOwnedParameters>
                <parameter Id="47ca47e7-94b2-464e-ae80-bd206dab4c9c" direction="Return" isUnique="false">
                  <elementDefinition Id="bb18e707-23e8-4aba-8707-0c3a35353214" />
                  <type_NamedElement>
                    <referencedTypeMoniker Id="10bb8f97-f852-412f-8c7d-c81490f9f614" LastKnownName="List&lt;SparePart&gt;" />
                  </type_NamedElement>
                </parameter>
              </operationHasOwnedParameters>
              <operationHasOwnedParameters>
                <parameter Id="6619d028-7264-4c61-9d38-d849c6cc7164" name="filterA" direction="In" isUnique="false">
                  <elementDefinition Id="fa726b75-51f4-4751-a1b3-120320243e44" />
                  <type_NamedElement>
                    <referencedTypeMoniker Id="df8dd8bd-98b9-4b9d-a18e-fcdb3b31fa72" LastKnownName="SparePart" />
                  </type_NamedElement>
                </parameter>
              </operationHasOwnedParameters>
              <operationHasOwnedParameters>
                <parameter Id="e34fad0e-dd90-401f-93dd-ed321e713446" name="filterB" direction="In" isUnique="false">
                  <elementDefinition Id="e62eb8c3-cd55-4f8e-8f74-b07b6b60c95a" />
                  <type_NamedElement>
                    <referencedTypeMoniker Id="df8dd8bd-98b9-4b9d-a18e-fcdb3b31fa72" LastKnownName="SparePart" />
                  </type_NamedElement>
                </parameter>
              </operationHasOwnedParameters>
              <operationHasOwnedParameters>
                <parameter Id="e38e141e-a27b-4560-b4b8-6bce6ceb8b39" name="Workshop" direction="In" isUnique="false">
                  <elementDefinition Id="2783d319-889a-4ca5-ac29-70daa7bf18bf" />
                  <type_NamedElement>
                    <referencedTypeMoniker Id="f4c65483-48fa-48c6-b1ba-774306746da9" LastKnownName="Workshop" />
                  </type_NamedElement>
                </parameter>
              </operationHasOwnedParameters>
              <operationHasOwnedParameters>
                <parameter Id="c85b4d79-c818-4df5-8b0c-35a41fe4ce86" name="quantityFromcount" direction="In" isUnique="false">
                  <elementDefinition Id="53b33173-720b-4d48-986a-c3cb0a868339" />
                  <type_NamedElement>
                    <referencedTypeMoniker Id="de578a74-cb65-4d29-833c-4c0b903c29db" LastKnownName="int" />
                  </type_NamedElement>
                </parameter>
              </operationHasOwnedParameters>
              <operationHasOwnedParameters>
                <parameter Id="ba0a6d0f-3a17-441a-a045-2164bf50fe12" name="quantityUntil" direction="In" isUnique="false">
                  <elementDefinition Id="5b45d041-2580-4769-995c-52cbd86cacaf" />
                  <type_NamedElement>
                    <referencedTypeMoniker Id="de578a74-cb65-4d29-833c-4c0b903c29db" LastKnownName="int" />
                  </type_NamedElement>
                </parameter>
              </operationHasOwnedParameters>
              <operationHasOwnedParameters>
                <parameter Id="1ac10261-98da-4c31-b422-14ff23e6b1ad" name="sortBy" direction="In" isUnique="false">
                  <elementDefinition Id="88fff2ac-45c6-4b16-a768-1cdee757196e" />
                  <type_NamedElement>
                    <referencedTypeMoniker Id="5432db89-8420-4f3f-bf54-d2b10dcc16ad" LastKnownName="string" />
                  </type_NamedElement>
                </parameter>
              </operationHasOwnedParameters>
              <operationHasOwnedParameters>
                <parameter Id="ad2a15f3-c212-4488-ad8d-e779a89a8ad4" name="desk" direction="In" isUnique="false">
                  <elementDefinition Id="da2333a0-86e4-43a7-8449-2ec24fd6aee8" />
                  <type_NamedElement>
                    <referencedTypeMoniker Id="6a45fed8-1689-4fa9-8e39-f876365db554" LastKnownName="bool" />
                  </type_NamedElement>
                </parameter>
              </operationHasOwnedParameters>
              <operationHasOwnedParameters>
                <parameter Id="195ae840-e33d-4028-be33-55131c60e28b" name="page" direction="In" isUnique="false">
                  <elementDefinition Id="2634bf23-d3f3-4e43-90c5-48fcca56c3a7" />
                  <type_NamedElement>
                    <referencedTypeMoniker Id="de578a74-cb65-4d29-833c-4c0b903c29db" LastKnownName="int" />
                  </type_NamedElement>
                </parameter>
              </operationHasOwnedParameters>
            </ownedParameters>
          </operation>
          <operation Id="7ca890c9-3ccf-4052-b43c-e69426acdfd3" name="GetById" isLeaf="false" isStatic="true" isAbstract="false" concurrency="Sequential" isQuery="false">
            <elementDefinition Id="9a40089a-a525-43c8-94d3-89c8c8278819" />
            <ownedParameters>
              <operationHasOwnedParameters>
                <parameter Id="88f1fc66-2f92-4dd9-a302-bfa11ec80ff8" name="Int" direction="In" isUnique="false">
                  <elementDefinition Id="9a2b92b3-d4a9-45ba-a8ed-64a5c1dbfb36" />
                </parameter>
              </operationHasOwnedParameters>
              <operationHasOwnedParameters>
                <parameter Id="96764211-5230-45f4-8d94-f1c4f95a0cc0" direction="Return" isUnique="false">
                  <elementDefinition Id="2a386493-fa65-41ca-b329-61850be97a14" />
                  <type_NamedElement>
                    <referencedTypeMoniker Id="df8dd8bd-98b9-4b9d-a18e-fcdb3b31fa72" LastKnownName="SparePart" />
                  </type_NamedElement>
                </parameter>
              </operationHasOwnedParameters>
            </ownedParameters>
          </operation>
        </ownedOperationsInternal>
      </class>
    </logicalClassDesignerModelHasTypes>
    <logicalClassDesignerModelHasTypes>
      <class Id="fefe1ea9-9a37-4d61-ab20-fdb71f38d1b3" name="OrderAtHome" isAbstract="false" isLeaf="false" isActiveClass="false">
        <elementDefinition Id="af7cf834-9864-4840-bb0a-f81bf9a2d0b7" />
        <generalsInternal>
          <generalization Id="e2d7ce7f-432d-4ccc-b568-88f3848b2d2c" isSubstitutable="false">
            <classMoniker Id="04d085bd-93e1-404d-b8cd-d5e6b85bd1ed" LastKnownName="Order" />
            <elementDefinition Id="9548652f-543d-4e97-a42e-4160b5f5a2c8" />
          </generalization>
        </generalsInternal>
        <ownedAttributesInternal>
          <property Id="fd0bb7e5-e0f3-4593-bbda-fe6b384bf087" name="Address" isLeaf="false" isStatic="false" isReadOnly="false" isUnique="false" isDerived="false" isDerivedUnion="false" aggregation="None" isComposite="false">
            <elementDefinition Id="e23154ce-2d22-46f2-baad-c8c510adaa13" />
            <type_NamedElement>
              <referencedTypeMoniker Id="faf4849f-8756-4979-b0da-605e57790912" LastKnownName="String" />
            </type_NamedElement>
          </property>
        </ownedAttributesInternal>
        <ownedOperationsInternal>
          <operation Id="dc8c1f8c-a764-44c3-ad24-0293f07b47ba" name="OrderAtHome" isLeaf="false" isStatic="false" isAbstract="false" concurrency="Sequential" isQuery="false">
            <elementDefinition Id="f18c2787-8201-47b0-868a-1cee78cf3ae9" />
            <ownedParameters>
              <operationHasOwnedParameters>
                <parameter Id="5bd0c547-22dc-4e25-92fc-33b713969911" direction="Return" isUnique="false">
                  <elementDefinition Id="a58003fe-0bf8-4f9b-9557-0747d7fb02f8" />
                  <type_NamedElement>
                    <referencedTypeMoniker Id="62e1c591-1fc8-4d49-889d-ba3d80faa959" LastKnownName="void" />
                  </type_NamedElement>
                </parameter>
              </operationHasOwnedParameters>
            </ownedParameters>
          </operation>
          <operation Id="890cab5b-bdd9-4de8-aeff-e68e3561b1ef" name="AddOrder" isLeaf="false" isStatic="false" isAbstract="false" concurrency="Sequential" isQuery="false">
            <elementDefinition Id="cf4db5fb-9f6f-41e7-b618-e54dcf59b3fd" />
            <ownedParameters>
              <operationHasOwnedParameters>
                <parameter Id="72904233-4396-43d8-bc41-67f667d97ea9" direction="Return" isUnique="false">
                  <elementDefinition Id="d0d0ed00-99d9-44e6-a9b1-2cc4c774f878" />
                  <type_NamedElement>
                    <referencedTypeMoniker Id="6a45fed8-1689-4fa9-8e39-f876365db554" LastKnownName="bool" />
                  </type_NamedElement>
                </parameter>
              </operationHasOwnedParameters>
            </ownedParameters>
          </operation>
          <operation Id="c8482371-81e1-4185-81e5-7d013779626b" name="EditOrder" isLeaf="false" isStatic="false" isAbstract="false" concurrency="Sequential" isQuery="false">
            <elementDefinition Id="d174f0f1-9efb-4071-8d14-9e31f20bc9ac" />
            <ownedParameters>
              <operationHasOwnedParameters>
                <parameter Id="8221c5a4-11dd-46e4-94a4-bb8841b523cc" direction="Return" isUnique="false">
                  <elementDefinition Id="916e66c4-f134-4a2d-bb77-e0963d7dde9a" />
                  <type_NamedElement>
                    <referencedTypeMoniker Id="6a45fed8-1689-4fa9-8e39-f876365db554" LastKnownName="bool" />
                  </type_NamedElement>
                </parameter>
              </operationHasOwnedParameters>
            </ownedParameters>
          </operation>
          <operation Id="a492ffd2-732a-4e3d-a342-7cfb44580488" name="GetVisits" isLeaf="false" isStatic="false" isAbstract="false" concurrency="Sequential" isQuery="false">
            <elementDefinition Id="1e77a325-044f-4131-8f5d-9217e13ec0fa" />
            <ownedParameters>
              <operationHasOwnedParameters>
                <parameter Id="e6f54f81-90b3-4043-a18a-540746f16d16" direction="Return" isUnique="false">
                  <elementDefinition Id="5f324c8f-a0f0-4074-9212-203ec5566dcf" />
                  <type_NamedElement>
                    <referencedTypeMoniker Id="b0b17692-ed70-44cf-ac5b-99a01cf9a1e6" LastKnownName="List&lt;Visit&gt;" />
                  </type_NamedElement>
                </parameter>
              </operationHasOwnedParameters>
            </ownedParameters>
          </operation>
        </ownedOperationsInternal>
      </class>
    </logicalClassDesignerModelHasTypes>
    <packageHasNamedElement>
      <referencedType Id="0dd4815a-6dbc-41c7-b719-9622cbfbbb8f" name="String" isAbstract="false" isLeaf="false" cachedFullName="String">
        <elementDefinition Id="59259974-6d55-42c6-b7bd-763d77ac8ef9" />
      </referencedType>
    </packageHasNamedElement>
    <logicalClassDesignerModelHasTypes>
      <class Id="8d202bca-fe5d-4075-9258-a7d9945a35a9" name="OrdersAtHomeList {static}" isAbstract="false" isLeaf="false" isActiveClass="false">
        <elementDefinition Id="57c9ddcf-203a-4db9-b379-5c58315dc9d5" />
        <targetEnds>
          <association Id="4f126a07-1379-48f4-b4ec-83ea10cb81e6" isDerived="false" sourceEndRoleName="OrdersAtHomeList {static}" targetEndRoleName="OrderAtHome" isLeaf="false" isAbstract="false">
            <classMoniker Id="fefe1ea9-9a37-4d61-ab20-fdb71f38d1b3" LastKnownName="OrderAtHome" />
            <relationshipOwnedElementsInternal>
              <associationHasOwnedEnds>
                <memberEnd Id="4a8c5dc6-d649-428c-a708-194964ae9898" name="OrdersAtHomeList {static}" isLeaf="false" isStatic="false" isReadOnly="false" isDerived="false" isDerivedUnion="false" aggregation="Shared" isComposite="false" isNavigableOwned="false">
                  <elementDefinition Id="4efb01c4-3d72-43f9-8b28-bd8c13f2c25d" />
                </memberEnd>
              </associationHasOwnedEnds>
              <associationHasOwnedEnds>
                <memberEnd Id="b62ba996-669a-4e4b-9ac6-3ee6169637f2" name="OrderAtHome" isLeaf="false" isStatic="false" isReadOnly="false" isDerived="false" isDerivedUnion="false" aggregation="None" isComposite="false">
                  <elementDefinition Id="c79fac7a-8dec-4daa-bffc-65ba12f76ee5" />
                </memberEnd>
              </associationHasOwnedEnds>
            </relationshipOwnedElementsInternal>
            <elementDefinition Id="203be345-d044-42ef-890e-baba8eb9362c" />
          </association>
        </targetEnds>
        <ownedOperationsInternal>
          <operation Id="0284ae94-5a5c-4e67-8456-a90bd96abf78" name="GetOrders" isLeaf="false" isStatic="true" isAbstract="false" concurrency="Sequential" isQuery="false">
            <elementDefinition Id="dc227dff-199f-4ac0-90ee-93bbb7e67ab9" />
            <ownedParameters>
              <operationHasOwnedParameters>
                <parameter Id="e9508b97-5105-4c5d-a292-2a1a9009da0f" direction="Return" isUnique="false">
                  <elementDefinition Id="9ee527ff-db64-495e-9598-0164b8e55f82" />
                  <type_NamedElement>
                    <referencedTypeMoniker Id="6cb3b83b-6d11-4c6c-8654-f14d4f9e7041" LastKnownName="List&lt;OrderAtHome&gt;" />
                  </type_NamedElement>
                </parameter>
              </operationHasOwnedParameters>
              <operationHasOwnedParameters>
                <parameter Id="4a3ed541-ed98-4da5-a587-7c2142ae4386" name="filterA" direction="In" isUnique="false">
                  <elementDefinition Id="9a7c9314-00de-4a27-88c9-ab6c7d67a9c7" />
                  <type_NamedElement>
                    <referencedTypeMoniker Id="2003ed98-f3fa-4914-b435-1ab35dccca81" LastKnownName="OrderAtHome" />
                  </type_NamedElement>
                </parameter>
              </operationHasOwnedParameters>
              <operationHasOwnedParameters>
                <parameter Id="c2ce94fe-0908-4a56-bdeb-b3d105f0014c" name="filterB" direction="In" isUnique="false">
                  <elementDefinition Id="838dc64b-d8dc-4070-9200-8353d2c8e909" />
                  <type_NamedElement>
                    <referencedTypeMoniker Id="2003ed98-f3fa-4914-b435-1ab35dccca81" LastKnownName="OrderAtHome" />
                  </type_NamedElement>
                </parameter>
              </operationHasOwnedParameters>
              <operationHasOwnedParameters>
                <parameter Id="914cb06e-e9ef-41f4-b607-d5d705db2865" name="client" direction="In" isUnique="false">
                  <elementDefinition Id="ea3d1013-6cd8-4e5e-91da-78b404239f79" />
                  <type_NamedElement>
                    <referencedTypeMoniker Id="7fb7c93f-995a-4b07-94af-09f2896d270c" LastKnownName="Client" />
                  </type_NamedElement>
                </parameter>
              </operationHasOwnedParameters>
              <operationHasOwnedParameters>
                <parameter Id="11e25150-a440-44c7-aab3-daf1c7ee13c4" name="activeOnly" direction="In" isUnique="false">
                  <elementDefinition Id="1fe1c1d9-5a98-423f-ba4b-4784c5a2e7fa" />
                  <type_NamedElement>
                    <referencedTypeMoniker Id="6a45fed8-1689-4fa9-8e39-f876365db554" LastKnownName="bool" />
                  </type_NamedElement>
                </parameter>
              </operationHasOwnedParameters>
              <operationHasOwnedParameters>
                <parameter Id="9de1eaf7-5518-406f-8721-c56155697f17" name="sortBy" direction="In" isUnique="false">
                  <elementDefinition Id="ccefaf0c-a783-4312-be72-f683e3dfe124" />
                  <type_NamedElement>
                    <referencedTypeMoniker Id="5432db89-8420-4f3f-bf54-d2b10dcc16ad" LastKnownName="string" />
                  </type_NamedElement>
                </parameter>
              </operationHasOwnedParameters>
              <operationHasOwnedParameters>
                <parameter Id="1f199c49-dd44-42c7-a3c4-9137d044b48a" name="desk" direction="In" isUnique="false">
                  <elementDefinition Id="260915ee-ce0a-46e1-9422-2a968ed62f48" />
                  <type_NamedElement>
                    <referencedTypeMoniker Id="6a45fed8-1689-4fa9-8e39-f876365db554" LastKnownName="bool" />
                  </type_NamedElement>
                </parameter>
              </operationHasOwnedParameters>
              <operationHasOwnedParameters>
                <parameter Id="a0074884-15d7-484f-be58-3830a2b522a8" name="count" direction="In" isUnique="false">
                  <elementDefinition Id="33e4d7f4-255d-4287-96af-bff6cf46a724" />
                  <type_NamedElement>
                    <referencedTypeMoniker Id="de578a74-cb65-4d29-833c-4c0b903c29db" LastKnownName="int" />
                  </type_NamedElement>
                </parameter>
              </operationHasOwnedParameters>
              <operationHasOwnedParameters>
                <parameter Id="d41ed546-cb2d-4796-9a0a-7188968d08bb" name="page" direction="In" isUnique="false">
                  <elementDefinition Id="033e449f-1e86-40d1-aaf3-b90566fbf644" />
                  <type_NamedElement>
                    <referencedTypeMoniker Id="de578a74-cb65-4d29-833c-4c0b903c29db" LastKnownName="int" />
                  </type_NamedElement>
                </parameter>
              </operationHasOwnedParameters>
            </ownedParameters>
          </operation>
          <operation Id="e82be1b8-15dc-4d8f-ad63-ef11836e8d25" name="GetById" isLeaf="false" isStatic="true" isAbstract="false" concurrency="Sequential" isQuery="false">
            <elementDefinition Id="60e0b145-5aa1-42be-bfbc-8f3f21fabcc3" />
            <ownedParameters>
              <operationHasOwnedParameters>
                <parameter Id="776ab493-587b-48bc-a3ba-fdc0807b2f51" name="Int" direction="In" isUnique="false">
                  <elementDefinition Id="745bbfb7-69c8-4f8a-8d97-957ffb764097" />
                </parameter>
              </operationHasOwnedParameters>
              <operationHasOwnedParameters>
                <parameter Id="970c456e-fb16-4d4a-817d-8a010ac9bdef" direction="Return" isUnique="false">
                  <elementDefinition Id="cbd5fedd-7002-49cc-9d9a-ed2aa44042a3" />
                  <type_NamedElement>
                    <referencedTypeMoniker Id="2003ed98-f3fa-4914-b435-1ab35dccca81" LastKnownName="OrderAtHome" />
                  </type_NamedElement>
                </parameter>
              </operationHasOwnedParameters>
            </ownedParameters>
          </operation>
        </ownedOperationsInternal>
      </class>
    </logicalClassDesignerModelHasTypes>
    <packageHasNamedElement>
      <referencedType Id="2003ed98-f3fa-4914-b435-1ab35dccca81" name="OrderAtHome" isAbstract="false" isLeaf="false" cachedFullName="CompServiceClassDiagram::OrderAtHome">
        <elementDefinition Id="af7cf834-9864-4840-bb0a-f81bf9a2d0b7" />
      </referencedType>
    </packageHasNamedElement>
    <packageHasNamedElement>
      <referencedType Id="6cb3b83b-6d11-4c6c-8654-f14d4f9e7041" name="List&lt;OrderAtHome&gt;" isAbstract="false" isLeaf="false" cachedFullName="List&lt;OrderAtHome&gt;">
        <elementDefinition Id="12f73632-0412-4cef-b42d-9473ad207520" />
      </referencedType>
    </packageHasNamedElement>
    <logicalClassDesignerModelHasTypes>
      <class Id="2cc2aa48-eb14-47fd-aa5c-160fa8768e9b" name="EmployeesList {static}" isAbstract="false" isLeaf="false" isActiveClass="false">
        <elementDefinition Id="505e4f06-b45e-4454-84fd-424ba42d7a75" />
        <targetEnds>
          <association Id="33d0a70b-cb05-4789-9f32-9482cb036c38" isDerived="false" sourceEndRoleName="EmployeesList {static}" targetEndRoleName="Employee " isLeaf="false" isAbstract="false">
            <classMoniker Id="9e4efbc8-78da-4018-bab1-5d0f33397b70" LastKnownName="Employee {abstract}" />
            <relationshipOwnedElementsInternal>
              <associationHasOwnedEnds>
                <memberEnd Id="e1c8912a-d978-400f-b847-6e59bd52b857" name="EmployeesList {static}" isLeaf="false" isStatic="false" isReadOnly="false" isDerived="false" isDerivedUnion="false" aggregation="Shared" isComposite="false" isNavigableOwned="false">
                  <elementDefinition Id="c4e22465-02dc-4b47-bacb-ae1a9dd8d596" />
                </memberEnd>
              </associationHasOwnedEnds>
              <associationHasOwnedEnds>
                <memberEnd Id="c44b281c-a024-4cff-a813-f6c9e3fee2a9" name="Employee " isLeaf="false" isStatic="false" isReadOnly="false" isDerived="false" isDerivedUnion="false" aggregation="None" isComposite="false">
                  <lowerValueInternal>
                    <literalString Id="610d96a3-2d32-42e6-931e-6cadafa00ad0" name="Lower" value="1">
                      <elementDefinition Id="dd6329a5-2e41-42bb-914b-b877a0ad0325" />
                    </literalString>
                  </lowerValueInternal>
                  <upperValueInternal>
                    <literalString Id="2d85a08d-46be-4ddc-b0c7-bac4ee992c3e" name="Upper" value="*">
                      <elementDefinition Id="4b7216a7-59c1-42f6-a204-cd826dec0ded" />
                    </literalString>
                  </upperValueInternal>
                  <elementDefinition Id="ae8bcfb3-c154-400b-8693-b9cfae3580bb" />
                </memberEnd>
              </associationHasOwnedEnds>
            </relationshipOwnedElementsInternal>
            <elementDefinition Id="4c50626b-5edd-4fa7-bfff-cb533fa3bcd5" />
          </association>
        </targetEnds>
        <ownedOperationsInternal>
          <operation Id="0243fb4a-ed84-4f5c-9b44-9c80c6a6e90a" name="GetEmployees" isLeaf="false" isStatic="true" isAbstract="false" concurrency="Sequential" isQuery="false">
            <elementDefinition Id="79bf9c10-d6a2-4019-9827-9769639349bd" />
            <ownedParameters>
              <operationHasOwnedParameters>
                <parameter Id="e3875de6-420a-4284-b79d-e1e7bda8b8b9" direction="Return" isUnique="false">
                  <elementDefinition Id="57de7344-79c8-428e-b074-b0cc731e08e2" />
                  <type_NamedElement>
                    <referencedTypeMoniker Id="76dd8cf8-c7cd-4fe3-b3c0-37937a0b4354" LastKnownName="List&lt;Employee&gt;" />
                  </type_NamedElement>
                </parameter>
              </operationHasOwnedParameters>
              <operationHasOwnedParameters>
                <parameter Id="8f1a3e88-50a4-4d07-88c2-df3c6aa04383" name="filterA" direction="In" isUnique="false">
                  <elementDefinition Id="69fa28fb-73de-47f4-afee-0188f0e73382" />
                  <type_NamedElement>
                    <referencedTypeMoniker Id="448d814c-c87b-42ed-9f0f-59cb5e5b0d67" LastKnownName="Employee" />
                  </type_NamedElement>
                </parameter>
              </operationHasOwnedParameters>
              <operationHasOwnedParameters>
                <parameter Id="b4cb15bf-4e8d-4749-9a96-2f5091de4c85" name="filterB" direction="In" isUnique="false">
                  <elementDefinition Id="0cb22f08-dac2-4546-a342-cb19a74917d5" />
                  <type_NamedElement>
                    <referencedTypeMoniker Id="448d814c-c87b-42ed-9f0f-59cb5e5b0d67" LastKnownName="Employee" />
                  </type_NamedElement>
                </parameter>
              </operationHasOwnedParameters>
              <operationHasOwnedParameters>
                <parameter Id="bc071dd6-9cfc-4548-836d-194c1ec2130c" name="sortBy" direction="In" isUnique="false">
                  <elementDefinition Id="ef5454af-2376-4c2a-97e8-47fe5692af52" />
                  <type_NamedElement>
                    <referencedTypeMoniker Id="5432db89-8420-4f3f-bf54-d2b10dcc16ad" LastKnownName="string" />
                  </type_NamedElement>
                </parameter>
              </operationHasOwnedParameters>
              <operationHasOwnedParameters>
                <parameter Id="ddf5b9bc-b40c-4a9a-a6ee-5544679db399" name="desk" direction="In" isUnique="false">
                  <elementDefinition Id="8b70f81b-1695-480c-b543-392b07875ebf" />
                  <type_NamedElement>
                    <referencedTypeMoniker Id="6a45fed8-1689-4fa9-8e39-f876365db554" LastKnownName="bool" />
                  </type_NamedElement>
                </parameter>
              </operationHasOwnedParameters>
              <operationHasOwnedParameters>
                <parameter Id="cc7f1159-0efa-4708-b38b-7069dc36a185" name="count" direction="In" isUnique="false">
                  <elementDefinition Id="8346ae5b-e224-4d8d-8962-a883668eb08c" />
                  <type_NamedElement>
                    <referencedTypeMoniker Id="de578a74-cb65-4d29-833c-4c0b903c29db" LastKnownName="int" />
                  </type_NamedElement>
                </parameter>
              </operationHasOwnedParameters>
              <operationHasOwnedParameters>
                <parameter Id="8ee6f1ac-227b-4ff8-a038-1298f119aae3" name="page" direction="In" isUnique="false">
                  <elementDefinition Id="996fdb7a-327c-4901-84d6-3109a216b948" />
                  <type_NamedElement>
                    <referencedTypeMoniker Id="de578a74-cb65-4d29-833c-4c0b903c29db" LastKnownName="int" />
                  </type_NamedElement>
                </parameter>
              </operationHasOwnedParameters>
            </ownedParameters>
          </operation>
          <operation Id="7cd34dc9-1afa-4dd8-a974-9b7b5aafd671" name="GetById" isLeaf="false" isStatic="true" isAbstract="false" concurrency="Sequential" isQuery="false">
            <elementDefinition Id="29671802-b76d-4eaa-a7bb-e7932fb0f868" />
            <ownedParameters>
              <operationHasOwnedParameters>
                <parameter Id="9899fcf4-c6e9-4291-a051-61032a645b68" name="Int" direction="In" isUnique="false">
                  <elementDefinition Id="1e8a7b1a-d9f6-426c-82bf-60f97b275ebe" />
                </parameter>
              </operationHasOwnedParameters>
              <operationHasOwnedParameters>
                <parameter Id="53d08618-0b99-4a5b-8ab5-f6d2f518acba" direction="Return" isUnique="false">
                  <elementDefinition Id="2373e657-4038-4ea9-81ee-70139880e7f0" />
                  <type_NamedElement>
                    <referencedTypeMoniker Id="448d814c-c87b-42ed-9f0f-59cb5e5b0d67" LastKnownName="Employee" />
                  </type_NamedElement>
                </parameter>
              </operationHasOwnedParameters>
            </ownedParameters>
          </operation>
        </ownedOperationsInternal>
      </class>
    </logicalClassDesignerModelHasTypes>
    <packageHasNamedElement>
      <referencedType Id="76dd8cf8-c7cd-4fe3-b3c0-37937a0b4354" name="List&lt;Employee&gt;" isAbstract="false" isLeaf="false" cachedFullName="List&lt;Employee&gt;">
        <elementDefinition Id="5b4236c0-e8ea-4169-a826-343f6073f6eb" />
      </referencedType>
    </packageHasNamedElement>
    <logicalClassDesignerModelHasTypes>
      <class Id="df214ad5-d1da-4292-b0e5-618549383bef" name="OrdersList {static}" isAbstract="false" isLeaf="false" isActiveClass="false">
        <elementDefinition Id="8556bbf8-4043-4c4f-8e33-d9598f241a1f" />
        <targetEnds>
          <association Id="8e11f4be-1c5d-4731-8310-e7b9dfc81534" isDerived="false" sourceEndRoleName="OrdersList" targetEndRoleName="Order" isLeaf="false" isAbstract="false">
            <classMoniker Id="04d085bd-93e1-404d-b8cd-d5e6b85bd1ed" LastKnownName="Order" />
            <relationshipOwnedElementsInternal>
              <associationHasOwnedEnds>
                <memberEnd Id="a0300d20-918f-4d61-93f9-2664cc25dd79" name="OrdersList" isLeaf="false" isStatic="false" isReadOnly="false" isDerived="false" isDerivedUnion="false" aggregation="Shared" isComposite="false" isNavigableOwned="false">
                  <elementDefinition Id="90ea4b77-4058-4d35-a6f6-fac0d26a0f40" />
                </memberEnd>
              </associationHasOwnedEnds>
              <associationHasOwnedEnds>
                <memberEnd Id="6deebdc6-6ecf-4aad-b9ca-04aed33d5ec0" name="Order" isLeaf="false" isStatic="false" isReadOnly="false" isDerived="false" isDerivedUnion="false" aggregation="None" isComposite="false">
                  <lowerValueInternal>
                    <literalString Id="3a329b6c-2c58-4da1-8f54-bf7f3fa7e390" name="Lower" value="1">
                      <elementDefinition Id="41bab853-0eae-41dc-8562-fc725755bb43" />
                    </literalString>
                  </lowerValueInternal>
                  <upperValueInternal>
                    <literalString Id="00e50a52-39a7-4feb-b015-00ad6421cebf" name="Upper" value="*">
                      <elementDefinition Id="0be61d0a-af97-4b7c-83cb-177a26d517c3" />
                    </literalString>
                  </upperValueInternal>
                  <elementDefinition Id="6e512af4-5043-4d97-a1d2-9ddadb3d60f9" />
                </memberEnd>
              </associationHasOwnedEnds>
            </relationshipOwnedElementsInternal>
            <elementDefinition Id="cc769101-b5c6-4922-a6e9-79c422dcdeca" />
          </association>
        </targetEnds>
        <ownedOperationsInternal>
          <operation Id="dd7cd2d6-f774-4644-b260-9fdeceeb8336" name="GetOrders" isLeaf="false" isStatic="true" isAbstract="false" concurrency="Sequential" isQuery="false">
            <elementDefinition Id="868347d0-1c7f-406a-a947-caacf02b1065" />
            <ownedParameters>
              <operationHasOwnedParameters>
                <parameter Id="c6dac1c1-5fdc-41ed-b682-3c7905ab545d" direction="Return" isUnique="false">
                  <elementDefinition Id="5abcaeae-aa56-43ca-ab7b-adb3c4f58ed1" />
                  <type_NamedElement>
                    <referencedTypeMoniker Id="1442db07-e3d8-4e3c-947e-806505dd7130" LastKnownName="List&lt;Order&gt;" />
                  </type_NamedElement>
                </parameter>
              </operationHasOwnedParameters>
              <operationHasOwnedParameters>
                <parameter Id="e6dc848c-7da8-4228-89d0-a082b8f78f33" name="filterA" direction="In" isUnique="false">
                  <elementDefinition Id="25752116-9c81-41e2-afe7-551ae3590a06" />
                  <type_NamedElement>
                    <referencedTypeMoniker Id="96762167-dba8-4e84-a426-d4426c479168" LastKnownName="Order" />
                  </type_NamedElement>
                </parameter>
              </operationHasOwnedParameters>
              <operationHasOwnedParameters>
                <parameter Id="3bdc6100-d3a4-40ba-949b-7d7a465e41db" name="filterB" direction="In" isUnique="false">
                  <elementDefinition Id="5581ab6a-0507-4941-a91d-adbf99fa0e2c" />
                  <type_NamedElement>
                    <referencedTypeMoniker Id="96762167-dba8-4e84-a426-d4426c479168" LastKnownName="Order" />
                  </type_NamedElement>
                </parameter>
              </operationHasOwnedParameters>
              <operationHasOwnedParameters>
                <parameter Id="37164cc8-e8e2-4253-8b6f-7113edf0d309" name="client" direction="In" isUnique="false">
                  <elementDefinition Id="9f6a7cd0-3b9c-49d5-850a-3e733fd95f9c" />
                  <type_NamedElement>
                    <referencedTypeMoniker Id="7fb7c93f-995a-4b07-94af-09f2896d270c" LastKnownName="Client" />
                  </type_NamedElement>
                </parameter>
              </operationHasOwnedParameters>
              <operationHasOwnedParameters>
                <parameter Id="52810fc5-33d9-448b-a10a-e829b570e2a6" name="activeOnly" direction="In" isUnique="false">
                  <elementDefinition Id="76d39ffd-ff12-4d3b-948a-3778fdc4df8d" />
                  <type_NamedElement>
                    <referencedTypeMoniker Id="6a45fed8-1689-4fa9-8e39-f876365db554" LastKnownName="bool" />
                  </type_NamedElement>
                </parameter>
              </operationHasOwnedParameters>
              <operationHasOwnedParameters>
                <parameter Id="930f46a8-e175-4623-b249-feed436f5845" name="sortBy" direction="In" isUnique="false">
                  <elementDefinition Id="00e3f5fb-084e-4dd5-8759-f1398a1e746b" />
                  <type_NamedElement>
                    <referencedTypeMoniker Id="5432db89-8420-4f3f-bf54-d2b10dcc16ad" LastKnownName="string" />
                  </type_NamedElement>
                </parameter>
              </operationHasOwnedParameters>
              <operationHasOwnedParameters>
                <parameter Id="ab498486-e351-43f8-8fb9-d6e789900fdd" name="desk" direction="In" isUnique="false">
                  <elementDefinition Id="ac30b99f-7c3d-46d7-b0e3-c9c2da8ee39f" />
                  <type_NamedElement>
                    <referencedTypeMoniker Id="6a45fed8-1689-4fa9-8e39-f876365db554" LastKnownName="bool" />
                  </type_NamedElement>
                </parameter>
              </operationHasOwnedParameters>
              <operationHasOwnedParameters>
                <parameter Id="b32fe268-6490-4784-aa7c-c92c564e1ad2" name="count" direction="In" isUnique="false">
                  <elementDefinition Id="f5dcdd23-3276-4027-989a-c50e52bbaea1" />
                  <type_NamedElement>
                    <referencedTypeMoniker Id="de578a74-cb65-4d29-833c-4c0b903c29db" LastKnownName="int" />
                  </type_NamedElement>
                </parameter>
              </operationHasOwnedParameters>
              <operationHasOwnedParameters>
                <parameter Id="00470414-a37b-4866-bc00-6a5bcf001e2f" name="page" direction="In" isUnique="false">
                  <elementDefinition Id="8634bb21-d7c1-45a8-a6a8-160c0dd7de03" />
                  <type_NamedElement>
                    <referencedTypeMoniker Id="de578a74-cb65-4d29-833c-4c0b903c29db" LastKnownName="int" />
                  </type_NamedElement>
                </parameter>
              </operationHasOwnedParameters>
            </ownedParameters>
          </operation>
          <operation Id="6478aab4-caa3-445c-8e51-d79217336e70" name="GetById" isLeaf="false" isStatic="true" isAbstract="false" concurrency="Sequential" isQuery="false">
            <elementDefinition Id="4d557512-8fde-4e2f-ba9d-454d5861fcc9" />
            <ownedParameters>
              <operationHasOwnedParameters>
                <parameter Id="650cac6a-6b43-4b58-905d-38fbbb808d97" direction="Return" isUnique="false">
                  <elementDefinition Id="895ec887-a8f4-41d0-a0b3-02b7a28205c5" />
                  <type_NamedElement>
                    <referencedTypeMoniker Id="96762167-dba8-4e84-a426-d4426c479168" LastKnownName="Order" />
                  </type_NamedElement>
                </parameter>
              </operationHasOwnedParameters>
              <operationHasOwnedParameters>
                <parameter Id="36a93e91-e47b-45dc-be36-13d3f29a9ca6" name="Int" direction="In" isUnique="false">
                  <elementDefinition Id="887f4a52-f1c1-487d-b43f-ed9598db6539" />
                </parameter>
              </operationHasOwnedParameters>
            </ownedParameters>
          </operation>
        </ownedOperationsInternal>
      </class>
    </logicalClassDesignerModelHasTypes>
    <packageHasNamedElement>
      <referencedType Id="afc7744e-e803-437f-814c-175324a339fb" name="TimeSpan" isAbstract="false" isLeaf="false" cachedFullName="TimeSpan">
        <elementDefinition Id="9d1e1c24-01a6-4bd5-9f84-3d1f8050902b" />
      </referencedType>
    </packageHasNamedElement>
    <packageHasNamedElement>
      <referencedType Id="a504101a-fcd4-4855-ab99-405c7225b8c5" name="List&lt;WorkshopTimetable&gt;" isAbstract="false" isLeaf="false" cachedFullName="List&lt;WorkshopTimetable&gt;">
        <elementDefinition Id="957b6588-43dd-4f08-9e5b-76f66c395aaf" />
      </referencedType>
    </packageHasNamedElement>
    <logicalClassDesignerModelHasTypes>
      <class Id="570dca5d-1874-4528-9f87-6e7995eff1ce" name="OrderSparePart" isAbstract="false" isLeaf="false" isActiveClass="false">
        <elementDefinition Id="e1defe16-18b3-498d-b93d-a4659b854e0f" />
        <targetEnds>
          <association Id="c1dacfe6-5820-438e-9510-e270ce180f17" isDerived="false" sourceEndRoleName="OrderSpareParts" targetEndRoleName="SparePart" isLeaf="false" isAbstract="false">
            <classMoniker Id="eeea4536-adc9-431d-8cb2-7cad87e92193" LastKnownName="SparePart" />
            <relationshipOwnedElementsInternal>
              <associationHasOwnedEnds>
                <memberEnd Id="2fcaa522-481b-439a-8f2a-2a3c99e88d05" name="OrderSpareParts" isLeaf="false" isStatic="false" isReadOnly="false" isDerived="false" isDerivedUnion="false" aggregation="Composite" isComposite="false" isNavigableOwned="false">
                  <lowerValueInternal>
                    <literalString Id="728768d8-eacf-4491-b961-5d8ae2719e91" name="Lower" value="0">
                      <elementDefinition Id="9371fe57-f40c-43c1-a73e-44d1672729e0" />
                    </literalString>
                  </lowerValueInternal>
                  <upperValueInternal>
                    <literalString Id="294c34e6-f1a4-432e-b061-aadc99e6fb4f" name="Upper" value="*">
                      <elementDefinition Id="dd151def-250b-4a32-9e3e-969fe2674043" />
                    </literalString>
                  </upperValueInternal>
                  <elementDefinition Id="09956ce5-cfa3-4ebe-a620-5daad0b8f163" />
                </memberEnd>
              </associationHasOwnedEnds>
              <associationHasOwnedEnds>
                <memberEnd Id="5156023d-c00c-4efd-aef9-3b028eb156e1" name="SparePart" isLeaf="false" isStatic="false" isReadOnly="false" isDerived="false" isDerivedUnion="false" aggregation="None" isComposite="true">
                  <elementDefinition Id="2d740581-d654-4a6e-934c-f31663d23a9b" />
                </memberEnd>
              </associationHasOwnedEnds>
            </relationshipOwnedElementsInternal>
            <elementDefinition Id="3a78e826-5e40-4c13-8ae8-0aa857f88656" />
          </association>
          <association Id="09e55118-167a-4f58-86a6-f938a286d91a" isDerived="false" sourceEndRoleName="OrderSparePart" targetEndRoleName="Order" isLeaf="false" isAbstract="false">
            <classMoniker Id="04d085bd-93e1-404d-b8cd-d5e6b85bd1ed" LastKnownName="Order" />
            <relationshipOwnedElementsInternal>
              <associationHasOwnedEnds>
                <memberEnd Id="c77f3a1a-4d8c-40da-bdfa-fd2273a234c2" name="OrderSparePart" isLeaf="false" isStatic="false" isReadOnly="false" isDerived="false" isDerivedUnion="false" aggregation="Composite" isComposite="false" isNavigableOwned="false">
                  <lowerValueInternal>
                    <literalString Id="914a75f5-a3cb-4999-b5bf-0022b26a7323" name="Lower" value="0">
                      <elementDefinition Id="9a0fb92c-a931-406a-9ecd-514680783a17" />
                    </literalString>
                  </lowerValueInternal>
                  <upperValueInternal>
                    <literalString Id="70f9263e-6dd5-4e28-8235-88f910d52f57" name="Upper" value="*">
                      <elementDefinition Id="cdb51f97-1560-4a34-8190-941ea54f84e5" />
                    </literalString>
                  </upperValueInternal>
                  <elementDefinition Id="f3b6f534-e934-4b3f-b8b9-907c91864220" />
                </memberEnd>
              </associationHasOwnedEnds>
              <associationHasOwnedEnds>
                <memberEnd Id="3ba311ed-ed71-403d-a9ac-e9721552eaa6" name="Order" isLeaf="false" isStatic="false" isReadOnly="false" isDerived="false" isDerivedUnion="false" aggregation="None" isComposite="true">
                  <elementDefinition Id="6f9e4ac0-0771-4312-a533-a8c5acdec887" />
                </memberEnd>
              </associationHasOwnedEnds>
            </relationshipOwnedElementsInternal>
            <elementDefinition Id="3d9436de-568e-4ecf-8ba1-0093a26e1af1" />
          </association>
        </targetEnds>
        <ownedAttributesInternal>
          <property Id="018678c6-9c96-42d4-900e-822306bf9475" name="SparePart" isLeaf="false" isStatic="false" isReadOnly="false" isUnique="false" isDerived="false" isDerivedUnion="false" aggregation="None" isComposite="false">
            <elementDefinition Id="2ae82373-478a-4aa3-86ea-06fcacf2f69a" />
            <type_NamedElement>
              <referencedTypeMoniker Id="643c642d-bc85-4c20-b8ce-cbf116cd79cd" LastKnownName="SparePart" />
            </type_NamedElement>
          </property>
          <property Id="2b213d96-5aab-4cfa-b2ed-3e2fe7ddc3bb" name="Order" isLeaf="false" isStatic="false" isReadOnly="false" isUnique="false" isDerived="false" isDerivedUnion="false" aggregation="None" isComposite="false">
            <elementDefinition Id="b7de7e9a-79fa-4a24-88d8-929119f6a090" />
            <type_NamedElement>
              <referencedTypeMoniker Id="96762167-dba8-4e84-a426-d4426c479168" LastKnownName="Order" />
            </type_NamedElement>
          </property>
        </ownedAttributesInternal>
        <ownedOperationsInternal>
          <operation Id="2bdfab9d-0ec0-4943-8b64-2555dc09766f" name="CalcPrice" isLeaf="false" isStatic="false" isAbstract="false" concurrency="Sequential" isQuery="false">
            <elementDefinition Id="36a8da65-a614-494e-af93-8549aeae956b" />
            <ownedParameters>
              <operationHasOwnedParameters>
                <parameter Id="ff43b703-3691-4552-9637-f809f82056fc" direction="Return" isUnique="false">
                  <elementDefinition Id="ee7dfdea-c538-4914-8818-7988a6d72c59" />
                  <type_NamedElement>
                    <referencedTypeMoniker Id="d0e2218a-5be7-46cf-97a2-091e3a6a80e0" LastKnownName="decimal" />
                  </type_NamedElement>
                </parameter>
              </operationHasOwnedParameters>
            </ownedParameters>
          </operation>
          <operation Id="2335c796-e450-4a94-b710-e4182e4e2344" name="GetBatchesInfo" isLeaf="false" isStatic="false" isAbstract="false" concurrency="Sequential" isQuery="false">
            <elementDefinition Id="4e181557-3b6b-407e-b786-a9da14f335de" />
            <ownedParameters>
              <operationHasOwnedParameters>
                <parameter Id="a0deea20-9ad6-4815-9748-e74a9dd8a95b" direction="Return" isUnique="false">
                  <elementDefinition Id="a1a7dd54-ae3f-417f-810c-ffd7eb4ff58e" />
                  <type_NamedElement>
                    <referencedTypeMoniker Id="b5531a86-0a26-4f67-88e2-aaa62ea9514d" LastKnownName="Dictionary&lt;Batch, Integer&gt;" />
                  </type_NamedElement>
                </parameter>
              </operationHasOwnedParameters>
            </ownedParameters>
          </operation>
          <operation Id="d234724a-d400-4e1e-8010-0af20a70805a" name="FindBatchesAuto" isLeaf="false" isStatic="false" isAbstract="false" concurrency="Sequential" isQuery="false">
            <elementDefinition Id="56e6205f-ee5d-422b-9610-2006861e23c6" />
            <ownedParameters>
              <operationHasOwnedParameters>
                <parameter Id="d56a020d-5c91-4410-a4ed-108c6c9629f4" direction="Return" isUnique="false">
                  <elementDefinition Id="a1e94333-178f-4edc-b773-24c44938d9c6" />
                  <type_NamedElement>
                    <referencedTypeMoniker Id="6a45fed8-1689-4fa9-8e39-f876365db554" LastKnownName="bool" />
                  </type_NamedElement>
                </parameter>
              </operationHasOwnedParameters>
              <operationHasOwnedParameters>
                <parameter Id="7a75c365-4423-4743-b5c6-3e7d462412ac" name="count" direction="In" isUnique="false">
                  <elementDefinition Id="88550f78-70ae-4411-ac38-0957a53bd788" />
                  <type_NamedElement>
                    <referencedTypeMoniker Id="bed62a32-5b87-4e40-9259-b99a5a7769a5" LastKnownName="Integer" />
                  </type_NamedElement>
                </parameter>
              </operationHasOwnedParameters>
            </ownedParameters>
          </operation>
          <operation Id="2aa3c355-82f7-41d5-a202-421bbe845b18" name="AddBatchInfo" isLeaf="false" isStatic="false" isAbstract="false" concurrency="Sequential" isQuery="false">
            <elementDefinition Id="b4300dd3-e6ff-47b5-9934-b08a05ad4d57" />
            <ownedParameters>
              <operationHasOwnedParameters>
                <parameter Id="47f37089-5199-4e86-b63b-d10a175f5157" direction="Return" isUnique="false">
                  <elementDefinition Id="d49fe918-190a-42e6-a517-3fb0139e9324" />
                  <type_NamedElement>
                    <referencedTypeMoniker Id="6a45fed8-1689-4fa9-8e39-f876365db554" LastKnownName="bool" />
                  </type_NamedElement>
                </parameter>
              </operationHasOwnedParameters>
              <operationHasOwnedParameters>
                <parameter Id="60110644-9890-4c41-b787-1b395da17b19" name="batch" direction="In" isUnique="false">
                  <elementDefinition Id="ec988f73-483d-41ed-a510-9305175e8535" />
                  <type_NamedElement>
                    <referencedTypeMoniker Id="a983ce7e-a30b-442b-8780-478ad8636aaf" LastKnownName="Batch" />
                  </type_NamedElement>
                </parameter>
              </operationHasOwnedParameters>
              <operationHasOwnedParameters>
                <parameter Id="ae19a03c-c2d0-47c5-98cc-a1b0b8f4ad91" name="quantity" direction="In" isUnique="false">
                  <elementDefinition Id="4629ffec-aaad-43d7-8b1e-0add4599ccf1" />
                  <type_NamedElement>
                    <referencedTypeMoniker Id="de578a74-cb65-4d29-833c-4c0b903c29db" LastKnownName="int" />
                  </type_NamedElement>
                </parameter>
              </operationHasOwnedParameters>
            </ownedParameters>
          </operation>
          <operation Id="aed082f6-f7c2-45d6-804b-b0d865211073" name="DelBatchInfo" isLeaf="false" isStatic="false" isAbstract="false" concurrency="Sequential" isQuery="false">
            <elementDefinition Id="b4e93ba4-5df2-4b57-85ea-296b9d0d5ced" />
            <ownedParameters>
              <operationHasOwnedParameters>
                <parameter Id="062e8879-f5fb-4ac8-bef6-01385c3719e8" direction="Return" isUnique="false">
                  <elementDefinition Id="fda5457f-1d79-4a49-ac52-7d86c760d864" />
                  <type_NamedElement>
                    <referencedTypeMoniker Id="6a45fed8-1689-4fa9-8e39-f876365db554" LastKnownName="bool" />
                  </type_NamedElement>
                </parameter>
              </operationHasOwnedParameters>
              <operationHasOwnedParameters>
                <parameter Id="3a0574ef-162b-45e0-85e8-600a8fc4936f" name="Batch" direction="In" isUnique="false">
                  <elementDefinition Id="b9141a4b-23e5-45c0-a051-628c363d4165" />
                </parameter>
              </operationHasOwnedParameters>
            </ownedParameters>
          </operation>
          <operation Id="b282d77c-d2f7-43ef-981d-4bf26bbf15ba" name="EditQuantity" isLeaf="false" isStatic="false" isAbstract="false" concurrency="Sequential" isQuery="false">
            <elementDefinition Id="3b50b5a6-7483-4335-8d79-ea48d4320f74" />
            <ownedParameters>
              <operationHasOwnedParameters>
                <parameter Id="f3e103bf-859a-464e-8d47-52aebb331ac1" direction="Return" isUnique="false">
                  <elementDefinition Id="4c023c25-52c8-4ec1-80cc-f2dbf5c48e85" />
                  <type_NamedElement>
                    <referencedTypeMoniker Id="6a45fed8-1689-4fa9-8e39-f876365db554" LastKnownName="bool" />
                  </type_NamedElement>
                </parameter>
              </operationHasOwnedParameters>
              <operationHasOwnedParameters>
                <parameter Id="d65bd03c-ea3e-48e0-a327-07d6bf23527e" name="Batch" direction="In" isUnique="false">
                  <elementDefinition Id="eeaddfde-c6f5-4761-a2a0-2d31e815a3da" />
                </parameter>
              </operationHasOwnedParameters>
              <operationHasOwnedParameters>
                <parameter Id="963f744a-d21a-4091-a9ff-961ab82767cc" name="Integer" direction="In" isUnique="false">
                  <elementDefinition Id="59c57706-402f-4489-9f8e-060014169634" />
                </parameter>
              </operationHasOwnedParameters>
            </ownedParameters>
          </operation>
          <operation Id="31eee75f-3e5d-46dd-a9f4-4fb947043a77" name="CheckBatchesDelivered" isLeaf="false" isStatic="false" isAbstract="false" concurrency="Sequential" isQuery="false">
            <elementDefinition Id="02edd69b-8f70-414e-80fe-4a26fe26899a" />
            <ownedParameters>
              <operationHasOwnedParameters>
                <parameter Id="b832329d-47d1-4835-897b-3101e8017776" direction="Return" isUnique="false">
                  <elementDefinition Id="6aa08e09-c8a9-4609-87bb-61cddfe6522b" />
                  <type_NamedElement>
                    <referencedTypeMoniker Id="6a45fed8-1689-4fa9-8e39-f876365db554" LastKnownName="bool" />
                  </type_NamedElement>
                </parameter>
              </operationHasOwnedParameters>
            </ownedParameters>
          </operation>
          <operation Id="9b0d0c7e-b618-4ba0-ba81-7cec6f5589c5" name="CalcSparePartQuantity" isLeaf="false" isStatic="false" isAbstract="false" concurrency="Sequential" isQuery="false">
            <elementDefinition Id="63e4f653-b5e2-4b2d-be07-9f71476e9173" />
            <ownedParameters>
              <operationHasOwnedParameters>
                <parameter Id="2dc659d5-2ddd-436b-bc83-441f2558266d" direction="Return" isUnique="false">
                  <elementDefinition Id="9fc1fc03-fd5a-421e-b66b-65b14337af2f" />
                  <type_NamedElement>
                    <referencedTypeMoniker Id="de578a74-cb65-4d29-833c-4c0b903c29db" LastKnownName="int" />
                  </type_NamedElement>
                </parameter>
              </operationHasOwnedParameters>
            </ownedParameters>
          </operation>
          <operation Id="6e5243b9-8ffe-403e-93b2-9240e988a70a" name="OrderSparePart" isLeaf="false" isStatic="false" isAbstract="false" concurrency="Sequential" isQuery="false">
            <elementDefinition Id="1eaa2e05-f36c-48e4-9dce-15ec5257ff89" />
            <ownedParameters>
              <operationHasOwnedParameters>
                <parameter Id="73ddb1f7-b7d2-4228-a988-9de7c1836893" direction="Return" isUnique="false">
                  <elementDefinition Id="95697065-28ab-4436-a1ad-67156d3e6f38" />
                  <type_NamedElement>
                    <referencedTypeMoniker Id="62e1c591-1fc8-4d49-889d-ba3d80faa959" LastKnownName="void" />
                  </type_NamedElement>
                </parameter>
              </operationHasOwnedParameters>
            </ownedParameters>
          </operation>
          <operation Id="4cef2096-d532-486e-8548-9588de108ef1" name="CalcInBatcPrice" isLeaf="false" isStatic="false" isAbstract="false" concurrency="Sequential" isQuery="false">
            <elementDefinition Id="8354f603-c0ec-4922-ba83-8c1199c17e38" />
            <ownedParameters>
              <operationHasOwnedParameters>
                <parameter Id="f39b89cf-df1e-4791-9469-79b02aacba43" direction="Return" isUnique="false">
                  <elementDefinition Id="8f677a97-af6f-4241-b7fb-f8e266da20ed" />
                  <type_NamedElement>
                    <referencedTypeMoniker Id="d0e2218a-5be7-46cf-97a2-091e3a6a80e0" LastKnownName="decimal" />
                  </type_NamedElement>
                </parameter>
              </operationHasOwnedParameters>
              <operationHasOwnedParameters>
                <parameter Id="3289fdcf-4559-4bc4-839d-f4de40f32174" name="batch" direction="In" isUnique="false">
                  <elementDefinition Id="06e81aa8-4f5c-4514-90e6-0f575081c017" />
                  <type_NamedElement>
                    <referencedTypeMoniker Id="a983ce7e-a30b-442b-8780-478ad8636aaf" LastKnownName="Batch" />
                  </type_NamedElement>
                </parameter>
              </operationHasOwnedParameters>
            </ownedParameters>
          </operation>
          <operation Id="f404748d-6976-4269-a6eb-5680f7e4a882" name="CheckBatch" isLeaf="false" isStatic="false" isAbstract="false" concurrency="Sequential" isQuery="false">
            <elementDefinition Id="87165c79-179a-4526-b8b7-d2fc4f10f786" />
            <ownedParameters>
              <operationHasOwnedParameters>
                <parameter Id="bc3c98e8-2427-4a06-bfad-4b68af49c1d3" name="batch" direction="In" isUnique="false">
                  <elementDefinition Id="84af1559-674c-47b7-8929-a1f6608a8452" />
                  <type_NamedElement>
                    <referencedTypeMoniker Id="a983ce7e-a30b-442b-8780-478ad8636aaf" LastKnownName="Batch" />
                  </type_NamedElement>
                </parameter>
              </operationHasOwnedParameters>
              <operationHasOwnedParameters>
                <parameter Id="803ad0a9-9ff1-4f1d-990e-a5c19983feb3" direction="Return" isUnique="false">
                  <elementDefinition Id="0cbbb59c-1b88-4fff-a322-a7a60b943906" />
                  <type_NamedElement>
                    <referencedTypeMoniker Id="6a45fed8-1689-4fa9-8e39-f876365db554" LastKnownName="bool" />
                  </type_NamedElement>
                </parameter>
              </operationHasOwnedParameters>
            </ownedParameters>
          </operation>
          <operation Id="7b3e34ef-38ce-4a96-9298-164279b64e1b" name="DelSparePart" isLeaf="false" isStatic="false" isAbstract="false" concurrency="Sequential" isQuery="false">
            <elementDefinition Id="54083d00-b7aa-423e-a80e-a5e157576e25" />
            <ownedParameters>
              <operationHasOwnedParameters>
                <parameter Id="b9b72e23-d9af-42da-8a2a-2e7f0512cce5" direction="Return" isUnique="false">
                  <elementDefinition Id="36d3a1ea-16a3-41cd-891a-1332d1ed7fc6" />
                  <type_NamedElement>
                    <referencedTypeMoniker Id="6a45fed8-1689-4fa9-8e39-f876365db554" LastKnownName="bool" />
                  </type_NamedElement>
                </parameter>
              </operationHasOwnedParameters>
            </ownedParameters>
          </operation>
        </ownedOperationsInternal>
      </class>
    </logicalClassDesignerModelHasTypes>
    <logicalClassDesignerModelHasTypes>
      <class Id="49e29943-c54c-45f2-9af3-97e7397fbc62" name="Role" isAbstract="false" isLeaf="false" isActiveClass="false">
        <elementDefinition Id="ab5e581b-fa61-4760-88a4-e6ea3211963d" />
        <targetEnds>
          <association Id="f255e8a3-e73b-42f0-8002-bb1c2b77e07c" isDerived="false" sourceEndRoleName="Role" targetEndRoleName="Permission" isLeaf="false" isAbstract="false">
            <classMoniker Id="1c7f5aed-f933-419b-ac1e-4eb43342fcb2" LastKnownName="Permission" />
            <relationshipOwnedElementsInternal>
              <associationHasOwnedEnds>
                <memberEnd Id="54c0fdf2-ea4b-43b1-94a7-49458d056ec3" name="Role" isLeaf="false" isStatic="false" isReadOnly="false" isDerived="false" isDerivedUnion="false" aggregation="Shared" isComposite="false" isNavigableOwned="false">
                  <lowerValueInternal>
                    <literalString Id="2c608717-bf36-4aaa-91dd-608218a168a1" name="Lower" value="1">
                      <elementDefinition Id="7370a815-5401-4067-8b9c-5afe5dd6fa82" />
                    </literalString>
                  </lowerValueInternal>
                  <upperValueInternal>
                    <literalString Id="77678926-2eb2-4554-8d41-39cfaf762765" name="Upper" value="*">
                      <elementDefinition Id="1b91820e-8ba0-43e5-b449-5cbf6addd63a" />
                    </literalString>
                  </upperValueInternal>
                  <elementDefinition Id="4e2eb8b4-a641-4a82-91e3-c5d3230b5597" />
                </memberEnd>
              </associationHasOwnedEnds>
              <associationHasOwnedEnds>
                <memberEnd Id="9ddeb0c8-98ef-4db2-b410-2bafcc65aa36" name="Permission" isLeaf="false" isStatic="false" isReadOnly="false" isDerived="false" isDerivedUnion="false" aggregation="None" isComposite="false">
                  <elementDefinition Id="9834e8e1-f6d6-4ea4-acc6-79e8c2cb085e" />
                </memberEnd>
              </associationHasOwnedEnds>
            </relationshipOwnedElementsInternal>
            <elementDefinition Id="c68688ec-14d0-402c-9541-abd3a3e4e203" />
          </association>
        </targetEnds>
        <ownedAttributesInternal>
          <property Id="2589244a-19b8-45a4-8366-e900279a10c2" name="id" isLeaf="false" isStatic="false" isReadOnly="false" isUnique="false" isDerived="false" isDerivedUnion="false" aggregation="None" isComposite="false">
            <elementDefinition Id="4d20f41e-1fb2-43c0-843e-925d162ed8b6" />
            <type_NamedElement>
              <referencedTypeMoniker Id="bed62a32-5b87-4e40-9259-b99a5a7769a5" LastKnownName="Integer" />
            </type_NamedElement>
          </property>
          <property Id="af0f6def-1dd3-4617-8d88-ea6c0ce61823" name="Name" isLeaf="false" isStatic="false" isReadOnly="false" isUnique="false" isDerived="false" isDerivedUnion="false" aggregation="None" isComposite="false">
            <elementDefinition Id="127a1d22-b29f-434f-9d01-1fcfc273a0cc" />
            <type_NamedElement>
              <referencedTypeMoniker Id="faf4849f-8756-4979-b0da-605e57790912" LastKnownName="String" />
            </type_NamedElement>
          </property>
        </ownedAttributesInternal>
        <ownedOperationsInternal>
          <operation Id="5a02ff9b-71ab-4a62-bafe-da1e4b0d69ae" name="GetPermissions" isLeaf="false" isStatic="false" isAbstract="false" concurrency="Sequential" isQuery="false">
            <elementDefinition Id="f8f10217-afe7-4b68-8d21-55325d143ce3" />
            <ownedParameters>
              <operationHasOwnedParameters>
                <parameter Id="8f87c81c-e9fc-4191-9c90-26c84dcca5e4" direction="Return" isUnique="false">
                  <elementDefinition Id="cc6d66d3-d511-4db2-b86c-081c610ea749" />
                  <type_NamedElement>
                    <referencedTypeMoniker Id="5c281f97-c251-4215-af6d-3d70ea9c6bba" LastKnownName="List&lt;Permission&gt;" />
                  </type_NamedElement>
                </parameter>
              </operationHasOwnedParameters>
            </ownedParameters>
          </operation>
          <operation Id="d73e6b0d-9486-4c8f-8b8d-456b9dd8bbe2" name="Role" isLeaf="false" isStatic="false" isAbstract="false" concurrency="Sequential" isQuery="false">
            <elementDefinition Id="aad8e21a-a9aa-4316-bafa-53f93850c188" />
            <ownedParameters>
              <operationHasOwnedParameters>
                <parameter Id="835afeea-f6f8-44b5-b7d1-b5a4358c9acc" direction="Return" isUnique="false">
                  <elementDefinition Id="d429038b-febb-4325-b294-03b46d70d857" />
                  <type_NamedElement>
                    <referencedTypeMoniker Id="62e1c591-1fc8-4d49-889d-ba3d80faa959" LastKnownName="void" />
                  </type_NamedElement>
                </parameter>
              </operationHasOwnedParameters>
            </ownedParameters>
          </operation>
          <operation Id="03b844e7-0ec3-4570-ad6c-a49bed03703f" name="AddRole" isLeaf="false" isStatic="false" isAbstract="false" concurrency="Sequential" isQuery="false">
            <elementDefinition Id="6a04cbae-791a-454f-ae70-32513bb9c3fb" />
            <ownedParameters>
              <operationHasOwnedParameters>
                <parameter Id="c5a1f862-12ee-4617-a5ec-11e7d2a401d3" direction="Return" isUnique="false">
                  <elementDefinition Id="51dc9969-5aee-4816-86d1-5beb6993714f" />
                  <type_NamedElement>
                    <referencedTypeMoniker Id="6a45fed8-1689-4fa9-8e39-f876365db554" LastKnownName="bool" />
                  </type_NamedElement>
                </parameter>
              </operationHasOwnedParameters>
            </ownedParameters>
          </operation>
          <operation Id="83d9f225-23fb-4c74-a13c-bc862040b105" name="DelRole" isLeaf="false" isStatic="false" isAbstract="false" concurrency="Sequential" isQuery="false">
            <elementDefinition Id="7bd7ca7f-78a3-4a0a-8449-6f53adc7b954" />
            <ownedParameters>
              <operationHasOwnedParameters>
                <parameter Id="af952495-5bbc-4d0f-be09-8ede62f89e9d" direction="Return" isUnique="false">
                  <elementDefinition Id="4a5a219b-bb76-448d-a077-433c3062745d" />
                  <type_NamedElement>
                    <referencedTypeMoniker Id="6a45fed8-1689-4fa9-8e39-f876365db554" LastKnownName="bool" />
                  </type_NamedElement>
                </parameter>
              </operationHasOwnedParameters>
            </ownedParameters>
          </operation>
          <operation Id="1d89b554-65a7-4c36-a871-6c6acc6e76b2" name="EditRole" isLeaf="false" isStatic="false" isAbstract="false" concurrency="Sequential" isQuery="false">
            <elementDefinition Id="c5cea7bf-df2c-42dc-b04b-17e18a483da7" />
            <ownedParameters>
              <operationHasOwnedParameters>
                <parameter Id="aa34e357-e42a-46d2-8b93-ff6e905877a9" direction="Return" isUnique="false">
                  <elementDefinition Id="578c91f2-f980-4fe0-9a13-0b21617c5f2b" />
                  <type_NamedElement>
                    <referencedTypeMoniker Id="6a45fed8-1689-4fa9-8e39-f876365db554" LastKnownName="bool" />
                  </type_NamedElement>
                </parameter>
              </operationHasOwnedParameters>
            </ownedParameters>
          </operation>
          <operation Id="8a033584-4144-4868-ae52-3918546d358c" name="AddPermission" isLeaf="false" isStatic="false" isAbstract="false" concurrency="Sequential" isQuery="false">
            <elementDefinition Id="230d1321-3791-41b4-9666-4aaba71677f3" />
            <ownedParameters>
              <operationHasOwnedParameters>
                <parameter Id="e6d50c66-0bd9-4be9-abe3-df4350a2f53b" name="permission" direction="In" isUnique="false">
                  <elementDefinition Id="7a288812-1f8b-4681-b4d0-26b533bd2677" />
                  <type_NamedElement>
                    <referencedTypeMoniker Id="d56bbbbe-e00b-4780-b8ab-6e56eef1a8fc" LastKnownName="Permission" />
                  </type_NamedElement>
                </parameter>
              </operationHasOwnedParameters>
              <operationHasOwnedParameters>
                <parameter Id="79f33b82-efe5-4974-9e52-fce4a9ed0d94" direction="Return" isUnique="false">
                  <elementDefinition Id="91cbb62a-f066-4110-9d19-92c6cb5088c2" />
                  <type_NamedElement>
                    <referencedTypeMoniker Id="6a45fed8-1689-4fa9-8e39-f876365db554" LastKnownName="bool" />
                  </type_NamedElement>
                </parameter>
              </operationHasOwnedParameters>
            </ownedParameters>
          </operation>
          <operation Id="9baafcac-555f-49f9-9bde-bd3285723eda" name="DelPermission" isLeaf="false" isStatic="false" isAbstract="false" concurrency="Sequential" isQuery="false">
            <elementDefinition Id="2cc801ca-79b6-48b4-9a29-c056480f59cb" />
            <ownedParameters>
              <operationHasOwnedParameters>
                <parameter Id="7704fe71-469c-4b60-b159-68e02fc291ed" name="permission" direction="In" isUnique="false">
                  <elementDefinition Id="22b35a8f-6bdf-4071-ade0-cfcd871a5a4b" />
                  <type_NamedElement>
                    <referencedTypeMoniker Id="d56bbbbe-e00b-4780-b8ab-6e56eef1a8fc" LastKnownName="Permission" />
                  </type_NamedElement>
                </parameter>
              </operationHasOwnedParameters>
              <operationHasOwnedParameters>
                <parameter Id="8fdee42c-b9f8-460a-9972-54f7f3269299" direction="Return" isUnique="false">
                  <elementDefinition Id="1d44459c-03fb-4582-9210-35c1dc61af8d" />
                  <type_NamedElement>
                    <referencedTypeMoniker Id="6a45fed8-1689-4fa9-8e39-f876365db554" LastKnownName="bool" />
                  </type_NamedElement>
                </parameter>
              </operationHasOwnedParameters>
            </ownedParameters>
          </operation>
          <operation Id="53f12fe3-41b6-4ea1-a8ad-ce31c2bed256" name="CheckPermission" isLeaf="false" isStatic="false" isAbstract="false" concurrency="Sequential" isQuery="false">
            <elementDefinition Id="97c4ab0d-5d94-4004-a701-1ba5e5b9c722" />
            <ownedParameters>
              <operationHasOwnedParameters>
                <parameter Id="04598104-23bb-4c28-a69e-edd8cd9eb84e" direction="Return" isUnique="false">
                  <elementDefinition Id="82882b7c-aa28-4345-b261-f4a21f2376e7" />
                  <type_NamedElement>
                    <referencedTypeMoniker Id="6a45fed8-1689-4fa9-8e39-f876365db554" LastKnownName="bool" />
                  </type_NamedElement>
                </parameter>
              </operationHasOwnedParameters>
              <operationHasOwnedParameters>
                <parameter Id="b81bb385-4854-4a4a-a25e-b405ac4f21a5" name="permission" direction="In" isUnique="false">
                  <elementDefinition Id="f670e9fc-1d1b-40a7-bbbf-7347f9122d9e" />
                  <type_NamedElement>
                    <referencedTypeMoniker Id="d56bbbbe-e00b-4780-b8ab-6e56eef1a8fc" LastKnownName="Permission" />
                  </type_NamedElement>
                </parameter>
              </operationHasOwnedParameters>
            </ownedParameters>
          </operation>
        </ownedOperationsInternal>
      </class>
    </logicalClassDesignerModelHasTypes>
    <logicalClassDesignerModelHasTypes>
      <class Id="1c7f5aed-f933-419b-ac1e-4eb43342fcb2" name="Permission" isAbstract="false" isLeaf="false" isActiveClass="false">
        <elementDefinition Id="0b93d8d6-c2f6-4ae8-b2f0-289a8424fe88" />
        <ownedAttributesInternal>
          <property Id="caeb2840-7d5b-448b-97a5-f7b3ca015a96" name="id" isLeaf="false" isStatic="false" isReadOnly="false" isUnique="false" isDerived="false" isDerivedUnion="false" aggregation="None" isComposite="false">
            <elementDefinition Id="3cfd2e1e-18a6-458d-9710-61d05527eb60" />
            <type_NamedElement>
              <referencedTypeMoniker Id="bed62a32-5b87-4e40-9259-b99a5a7769a5" LastKnownName="Integer" />
            </type_NamedElement>
          </property>
          <property Id="9d8ff00a-91c5-4bb4-843c-5b210ea61f97" name="Name" isLeaf="false" isStatic="false" isReadOnly="false" isUnique="false" isDerived="false" isDerivedUnion="false" aggregation="None" isComposite="false">
            <elementDefinition Id="810fd82f-fe7f-4ed6-84e7-d12834e240f5" />
            <type_NamedElement>
              <referencedTypeMoniker Id="faf4849f-8756-4979-b0da-605e57790912" LastKnownName="String" />
            </type_NamedElement>
          </property>
          <property Id="170ab216-ddaa-43fb-adf9-eb8b4e4d1238" name="Code" isLeaf="false" isStatic="false" isReadOnly="false" isUnique="false" isDerived="false" isDerivedUnion="false" aggregation="None" isComposite="false">
            <elementDefinition Id="c6bc32ad-7b17-4044-ae47-d77592172b51" />
            <type_NamedElement>
              <referencedTypeMoniker Id="faf4849f-8756-4979-b0da-605e57790912" LastKnownName="String" />
            </type_NamedElement>
          </property>
        </ownedAttributesInternal>
        <ownedOperationsInternal>
          <operation Id="17d1e7e5-7cc6-4ced-9982-6cec1f2276c8" name="Permission" isLeaf="false" isStatic="false" isAbstract="false" concurrency="Sequential" isQuery="false">
            <elementDefinition Id="e6eac26a-7d8a-48c5-b538-6a5f34a1ff65" />
            <ownedParameters>
              <operationHasOwnedParameters>
                <parameter Id="a6bf425a-7ee8-41cd-8419-e63ceeeb1503" direction="Return" isUnique="false">
                  <elementDefinition Id="444c2c8d-17c9-4a41-86f7-5a20decb46a0" />
                  <type_NamedElement>
                    <referencedTypeMoniker Id="62e1c591-1fc8-4d49-889d-ba3d80faa959" LastKnownName="void" />
                  </type_NamedElement>
                </parameter>
              </operationHasOwnedParameters>
            </ownedParameters>
          </operation>
        </ownedOperationsInternal>
      </class>
    </logicalClassDesignerModelHasTypes>
    <packageHasNamedElement>
      <referencedType Id="5c281f97-c251-4215-af6d-3d70ea9c6bba" name="List&lt;Permission&gt;" isAbstract="false" isLeaf="false" cachedFullName="List&lt;Permission&gt;">
        <elementDefinition Id="fb77eeff-92c9-4ca6-8c95-9bc31dfac64a" />
      </referencedType>
    </packageHasNamedElement>
    <packageHasNamedElement>
      <referencedType Id="dcabf460-1745-43b0-bd60-733bb6dd04c2" name="Role" isAbstract="false" isLeaf="false" cachedFullName="CompServiceClassDiagram::Role">
        <elementDefinition Id="ab5e581b-fa61-4760-88a4-e6ea3211963d" />
      </referencedType>
    </packageHasNamedElement>
    <logicalClassDesignerModelHasTypes>
      <class Id="593cb2ed-8cab-400f-84d9-404853805b39" name="Batch" isAbstract="false" isLeaf="false" isActiveClass="false">
        <elementDefinition Id="1459b137-3ab1-49cb-b736-a72c4b00e2c5" />
        <targetEnds>
          <association Id="b577bd92-8d3d-4f66-8c3e-755e796d79a1" isDerived="false" sourceEndRoleName="Batch" targetEndRoleName="SparePart" isLeaf="false" isAbstract="false">
            <classMoniker Id="eeea4536-adc9-431d-8cb2-7cad87e92193" LastKnownName="SparePart" />
            <relationshipOwnedElementsInternal>
              <associationHasOwnedEnds>
                <memberEnd Id="de165664-d6e3-402f-97d2-effccc5b7d99" name="Batch" isLeaf="false" isStatic="false" isReadOnly="false" isDerived="false" isDerivedUnion="false" aggregation="Shared" isComposite="false" isNavigableOwned="false">
                  <lowerValueInternal>
                    <literalString Id="99fff58e-ae01-4607-9911-f97469a120cc" name="Lower" value="0">
                      <elementDefinition Id="2e41b51d-52c5-479c-b547-698e7fc64d8e" />
                    </literalString>
                  </lowerValueInternal>
                  <upperValueInternal>
                    <literalString Id="16b614fc-370c-4db1-a313-fa01f161ee31" name="Upper" value="*">
                      <elementDefinition Id="5357fb9d-6fd1-4f70-9ce1-7552a8091162" />
                    </literalString>
                  </upperValueInternal>
                  <elementDefinition Id="5677eb77-405e-4f93-a4b0-7d17c84fbeee" />
                </memberEnd>
              </associationHasOwnedEnds>
              <associationHasOwnedEnds>
                <memberEnd Id="355b2990-8bf8-4308-bec8-f9759bc1641a" name="SparePart" isLeaf="false" isStatic="false" isReadOnly="false" isDerived="false" isDerivedUnion="false" aggregation="None" isComposite="false">
                  <lowerValueInternal>
                    <literalString Id="3ae89522-bcc3-49ac-a61d-0177e532fc67" name="Lower" value="1">
                      <elementDefinition Id="c3b233ae-dbea-43e6-b28d-3ada214d068a" />
                    </literalString>
                  </lowerValueInternal>
                  <upperValueInternal>
                    <literalString Id="a3984813-6a31-4202-aded-f8b13d45cdcf" name="Upper" value="*">
                      <elementDefinition Id="623c9775-407a-4b6d-ba15-251117b61093" />
                    </literalString>
                  </upperValueInternal>
                  <elementDefinition Id="aa689fcb-2946-4f13-a669-8df70053e61e" />
                </memberEnd>
              </associationHasOwnedEnds>
            </relationshipOwnedElementsInternal>
            <elementDefinition Id="a883a815-497e-4bd1-b21d-0c84ff2a19b9" />
          </association>
        </targetEnds>
        <ownedAttributesInternal>
          <property Id="78135280-c503-4c5c-b721-137a51cb8f7a" name="id" isLeaf="false" isStatic="false" isReadOnly="false" isUnique="false" isDerived="false" isDerivedUnion="false" aggregation="None" isComposite="false">
            <elementDefinition Id="490854f1-dae3-4116-ad4b-6c2bbc93ed04" />
            <type_NamedElement>
              <referencedTypeMoniker Id="bed62a32-5b87-4e40-9259-b99a5a7769a5" LastKnownName="Integer" />
            </type_NamedElement>
          </property>
          <property Id="ddd57e52-5adf-48a4-89db-986dd780f3de" name="Workshop" isLeaf="false" isStatic="false" isReadOnly="false" isUnique="false" isDerived="false" isDerivedUnion="false" aggregation="None" isComposite="false">
            <elementDefinition Id="ccfb13d7-78d0-452c-9f74-f257f75823ac" />
            <type_NamedElement>
              <referencedTypeMoniker Id="f4c65483-48fa-48c6-b1ba-774306746da9" LastKnownName="Workshop" />
            </type_NamedElement>
          </property>
          <property Id="fd23c088-dc27-4a91-a23a-b0ebb942868c" name="DateDelivered" isLeaf="false" isStatic="false" isReadOnly="false" isUnique="false" isDerived="false" isDerivedUnion="false" aggregation="None" isComposite="false">
            <elementDefinition Id="a2a5e148-cf12-4ae9-8e47-c0cc23e86100" />
            <type_NamedElement>
              <referencedTypeMoniker Id="5e95a766-896f-41c7-8951-778ddf708d7a" LastKnownName="DateTime" />
            </type_NamedElement>
          </property>
          <property Id="8614a189-ae0f-4bef-827c-a8d249671c7f" name="DelTime" isLeaf="false" isStatic="false" isReadOnly="false" isUnique="false" isDerived="false" isDerivedUnion="false" aggregation="None" isComposite="false">
            <elementDefinition Id="96fca284-9cbf-4c7e-ba3a-1130071ba022" />
            <type_NamedElement>
              <referencedTypeMoniker Id="5e95a766-896f-41c7-8951-778ddf708d7a" LastKnownName="DateTime" />
            </type_NamedElement>
          </property>
          <property Id="0a4f9de9-50b4-4aa0-9580-25f4b43e8d58" name="TrackNumber" isLeaf="false" isStatic="false" isReadOnly="false" isUnique="false" isDerived="false" isDerivedUnion="false" aggregation="None" isComposite="false">
            <elementDefinition Id="2ebc5b29-c9b1-4601-87a3-c6f021b94fe0" />
            <type_NamedElement>
              <referencedTypeMoniker Id="faf4849f-8756-4979-b0da-605e57790912" LastKnownName="String" />
            </type_NamedElement>
          </property>
          <property Id="1d786429-c031-4eea-8dd5-c9adbc9d52b9" name="Price" isLeaf="false" isStatic="false" isReadOnly="false" isUnique="false" isDerived="false" isDerivedUnion="false" aggregation="None" isComposite="false">
            <elementDefinition Id="f0cdc23f-64f1-4bf1-97e9-e077ea4542ba" />
            <type_NamedElement>
              <referencedTypeMoniker Id="d0e2218a-5be7-46cf-97a2-091e3a6a80e0" LastKnownName="decimal" />
            </type_NamedElement>
          </property>
        </ownedAttributesInternal>
        <ownedOperationsInternal>
          <operation Id="e3a15f03-acc8-40e4-8a00-5624a43306ef" name="CalcFinalPrice" isLeaf="false" isStatic="false" isAbstract="false" concurrency="Sequential" isQuery="false">
            <elementDefinition Id="1a3d4ef3-8d49-4b57-9d6c-e59ff0754bed" />
            <ownedParameters>
              <operationHasOwnedParameters>
                <parameter Id="79ac8465-1025-48ec-b2b8-83e2c362d490" direction="Return" isUnique="false">
                  <elementDefinition Id="9da206c3-df7b-4a35-a5c5-3803c08c1570" />
                  <type_NamedElement>
                    <referencedTypeMoniker Id="d0e2218a-5be7-46cf-97a2-091e3a6a80e0" LastKnownName="decimal" />
                  </type_NamedElement>
                </parameter>
              </operationHasOwnedParameters>
            </ownedParameters>
          </operation>
          <operation Id="c56f31a1-96f0-4f87-8e73-97a7ee3457dd" name="Batch" isLeaf="false" isStatic="false" isAbstract="false" concurrency="Sequential" isQuery="false">
            <elementDefinition Id="efd1170e-123a-4954-bb84-6670153cd0b6" />
            <ownedParameters>
              <operationHasOwnedParameters>
                <parameter Id="fa9156a0-8ce0-4818-95b3-d3d02190f1dc" direction="Return" isUnique="false">
                  <elementDefinition Id="e85705c7-e64c-447b-8b30-ef7cc5676aa7" />
                  <type_NamedElement>
                    <referencedTypeMoniker Id="62e1c591-1fc8-4d49-889d-ba3d80faa959" LastKnownName="void" />
                  </type_NamedElement>
                </parameter>
              </operationHasOwnedParameters>
            </ownedParameters>
          </operation>
          <operation Id="b26bead8-106a-421a-a631-6f648837dd96" name="AddBatch" isLeaf="false" isStatic="false" isAbstract="false" concurrency="Sequential" isQuery="false">
            <elementDefinition Id="09f5e2a1-630a-41ab-a504-d3fc8ff2664b" />
            <ownedParameters>
              <operationHasOwnedParameters>
                <parameter Id="9e1a1dff-f7d5-4995-888b-15c39388b957" direction="Return" isUnique="false">
                  <elementDefinition Id="4480c12b-c563-4c70-bcd7-f897c8572625" />
                  <type_NamedElement>
                    <referencedTypeMoniker Id="6a45fed8-1689-4fa9-8e39-f876365db554" LastKnownName="bool" />
                  </type_NamedElement>
                </parameter>
              </operationHasOwnedParameters>
            </ownedParameters>
          </operation>
          <operation Id="0e99dbe1-3e4c-48d3-9efa-8f84bc24fe43" name="DelBatch" isLeaf="false" isStatic="false" isAbstract="false" concurrency="Sequential" isQuery="false">
            <elementDefinition Id="08010ab6-95ee-40e1-97b4-2b6c3f711bb3" />
            <ownedParameters>
              <operationHasOwnedParameters>
                <parameter Id="7eee80db-2e62-4e7e-9eb5-56b448fc2e0b" direction="Return" isUnique="false">
                  <elementDefinition Id="2d8f25c6-8147-4755-8c9e-ae116f6b3d91" />
                  <type_NamedElement>
                    <referencedTypeMoniker Id="6a45fed8-1689-4fa9-8e39-f876365db554" LastKnownName="bool" />
                  </type_NamedElement>
                </parameter>
              </operationHasOwnedParameters>
            </ownedParameters>
          </operation>
          <operation Id="5ef63253-c276-47eb-bfb9-2f453b7c75ab" name="GetCountLeft" isLeaf="false" isStatic="false" isAbstract="false" concurrency="Sequential" isQuery="false">
            <elementDefinition Id="f3805936-f7fc-4454-9eaf-d6b8e8d97436" />
            <ownedParameters>
              <operationHasOwnedParameters>
                <parameter Id="6fea232c-6adf-4009-9f60-5ca002cf1a28" direction="Return" isUnique="false">
                  <elementDefinition Id="fb80fe51-beed-41c7-8538-358573a9e86a" />
                  <type_NamedElement>
                    <referencedTypeMoniker Id="bed62a32-5b87-4e40-9259-b99a5a7769a5" LastKnownName="Integer" />
                  </type_NamedElement>
                </parameter>
              </operationHasOwnedParameters>
              <operationHasOwnedParameters>
                <parameter Id="db687189-89b8-4985-944a-430f45878da8" name="sparePart" direction="In" isUnique="false">
                  <elementDefinition Id="c5d8f585-68e7-4415-a169-ea5dea198c5c" />
                  <type_NamedElement>
                    <referencedTypeMoniker Id="df8dd8bd-98b9-4b9d-a18e-fcdb3b31fa72" LastKnownName="SparePart" />
                  </type_NamedElement>
                </parameter>
              </operationHasOwnedParameters>
            </ownedParameters>
          </operation>
          <operation Id="191e9b3c-4d3e-4ac2-99d4-cd0b0a8d4b8c" name="GetSpareParts" isLeaf="false" isStatic="false" isAbstract="false" concurrency="Sequential" isQuery="false">
            <elementDefinition Id="d0ce755e-cbdc-42ee-a2b0-95eb44765c2f" />
            <ownedParameters>
              <operationHasOwnedParameters>
                <parameter Id="ce2ffe49-40f1-409a-9690-b924b1420203" direction="Return" isUnique="false">
                  <elementDefinition Id="c1305b4c-5eb5-4762-afcf-470b4748122c" />
                  <type_NamedElement>
                    <referencedTypeMoniker Id="08265551-2095-47de-bdb0-a7af11d7a3d7" LastKnownName="List&lt;BatchSpareParts&gt;" />
                  </type_NamedElement>
                </parameter>
              </operationHasOwnedParameters>
            </ownedParameters>
          </operation>
          <operation Id="810b7cf4-0f67-4cb0-84d8-6d29d0353adf" name="IsSpent" isLeaf="false" isStatic="false" isAbstract="false" concurrency="Sequential" isQuery="false">
            <elementDefinition Id="8433c9f5-c09e-420f-acb7-674735aaf8f6" />
            <ownedParameters>
              <operationHasOwnedParameters>
                <parameter Id="d147ff28-285d-471c-8793-b4e85e5434e4" direction="Return" isUnique="false">
                  <elementDefinition Id="db1e2b27-7ac2-4686-8b1c-7a71da548a41" />
                  <type_NamedElement>
                    <referencedTypeMoniker Id="6a45fed8-1689-4fa9-8e39-f876365db554" LastKnownName="bool" />
                  </type_NamedElement>
                </parameter>
              </operationHasOwnedParameters>
            </ownedParameters>
          </operation>
          <operation Id="35ee1e6a-2b8c-4bd3-93ce-947a7162879b" name="AddSparePart" isLeaf="false" isStatic="false" isAbstract="false" concurrency="Sequential" isQuery="false">
            <elementDefinition Id="cae84a92-a73e-48e9-b7ea-bcb0a0543bf6" />
            <ownedParameters>
              <operationHasOwnedParameters>
                <parameter Id="bdbe19bd-1d01-424a-8cf9-0b11b67564e7" name="sparePart" direction="In" isUnique="false">
                  <elementDefinition Id="aea0292c-4116-45ea-99b4-5c0f86dded14" />
                  <type_NamedElement>
                    <referencedTypeMoniker Id="cf414de7-1932-44ee-a68d-62f336d10035" LastKnownName="BatchSparePart" />
                  </type_NamedElement>
                </parameter>
              </operationHasOwnedParameters>
              <operationHasOwnedParameters>
                <parameter Id="874d5376-a74a-4fa8-a31c-2f280d6d01a6" direction="Return" isUnique="false">
                  <elementDefinition Id="87ebc217-17a6-42fd-ad9d-094385ca9a8f" />
                  <type_NamedElement>
                    <referencedTypeMoniker Id="6a45fed8-1689-4fa9-8e39-f876365db554" LastKnownName="bool" />
                  </type_NamedElement>
                </parameter>
              </operationHasOwnedParameters>
            </ownedParameters>
          </operation>
          <operation Id="8defe106-24d1-4341-bc17-3174d0784dab" name="DelSparePart" isLeaf="false" isStatic="false" isAbstract="false" concurrency="Sequential" isQuery="false">
            <elementDefinition Id="12d0d194-9f68-4cc5-9f05-22059189c627" />
            <ownedParameters>
              <operationHasOwnedParameters>
                <parameter Id="cab7b065-8880-4630-a8e5-ea4240bc8757" name="sparePart" direction="In" isUnique="false">
                  <elementDefinition Id="cbb48448-be83-4a5b-82bf-755f96574a73" />
                  <type_NamedElement>
                    <referencedTypeMoniker Id="cf414de7-1932-44ee-a68d-62f336d10035" LastKnownName="BatchSparePart" />
                  </type_NamedElement>
                </parameter>
              </operationHasOwnedParameters>
              <operationHasOwnedParameters>
                <parameter Id="f307f334-652f-42ad-a887-496497e111a4" direction="Return" isUnique="false">
                  <elementDefinition Id="b17a933e-4cb3-4e4d-b3aa-841d39aca06b" />
                  <type_NamedElement>
                    <referencedTypeMoniker Id="6a45fed8-1689-4fa9-8e39-f876365db554" LastKnownName="bool" />
                  </type_NamedElement>
                </parameter>
              </operationHasOwnedParameters>
            </ownedParameters>
          </operation>
          <operation Id="54b18869-fc39-4148-af75-78ae0aae61a2" name="EditSparePart" isLeaf="false" isStatic="false" isAbstract="false" concurrency="Sequential" isQuery="false">
            <elementDefinition Id="50d3f890-d5fd-4d80-ba46-ef33cee5a6ac" />
            <ownedParameters>
              <operationHasOwnedParameters>
                <parameter Id="c83e630c-f905-40e4-a021-41076b799dd1" name="sparePart" direction="In" isUnique="false">
                  <elementDefinition Id="0d96a464-b127-4bd6-a499-a6d5b43dd91b" />
                  <type_NamedElement>
                    <referencedTypeMoniker Id="cf414de7-1932-44ee-a68d-62f336d10035" LastKnownName="BatchSparePart" />
                  </type_NamedElement>
                </parameter>
              </operationHasOwnedParameters>
              <operationHasOwnedParameters>
                <parameter Id="e4953272-8e8c-487c-aa3e-2d4bfbdd5309" direction="Return" isUnique="false">
                  <elementDefinition Id="b9846d72-9365-47a2-9796-84d6f813abe4" />
                  <type_NamedElement>
                    <referencedTypeMoniker Id="6a45fed8-1689-4fa9-8e39-f876365db554" LastKnownName="bool" />
                  </type_NamedElement>
                </parameter>
              </operationHasOwnedParameters>
            </ownedParameters>
          </operation>
          <operation Id="cf23769f-cdf4-4074-9310-b017fa099225" name="GetSparePart" isLeaf="false" isStatic="false" isAbstract="false" concurrency="Sequential" isQuery="false">
            <elementDefinition Id="97146825-bc01-46c1-b52d-be944d7b6961" />
            <ownedParameters>
              <operationHasOwnedParameters>
                <parameter Id="45d15456-7c61-454d-9635-7ac243adc2c0" name="id" direction="In" isUnique="false">
                  <elementDefinition Id="da369ddf-9f66-458a-9e3c-12e6c4d3f064" />
                  <type_NamedElement>
                    <referencedTypeMoniker Id="de578a74-cb65-4d29-833c-4c0b903c29db" LastKnownName="int" />
                  </type_NamedElement>
                </parameter>
              </operationHasOwnedParameters>
              <operationHasOwnedParameters>
                <parameter Id="44e1eb02-58c6-4039-aa94-637ec50da9ea" direction="Return" isUnique="false">
                  <elementDefinition Id="cf030b22-1a53-44a5-a3a0-d5e9733e9daa" />
                  <type_NamedElement>
                    <referencedTypeMoniker Id="cf414de7-1932-44ee-a68d-62f336d10035" LastKnownName="BatchSparePart" />
                  </type_NamedElement>
                </parameter>
              </operationHasOwnedParameters>
            </ownedParameters>
          </operation>
          <operation Id="b0e154c8-a778-49a4-8335-8ec83f8fe540" name="CheckSparePart" isLeaf="false" isStatic="false" isAbstract="false" concurrency="Sequential" isQuery="false">
            <elementDefinition Id="8cac6be2-ef4c-41df-8a65-01160a23524d" />
            <ownedParameters>
              <operationHasOwnedParameters>
                <parameter Id="a4a8809b-3d19-4fcd-ab9b-24c4f144f53c" name="sparePart" direction="In" isUnique="false">
                  <elementDefinition Id="2788f0a1-c59e-4b40-847d-13c8da679724" />
                  <type_NamedElement>
                    <referencedTypeMoniker Id="df8dd8bd-98b9-4b9d-a18e-fcdb3b31fa72" LastKnownName="SparePart" />
                  </type_NamedElement>
                </parameter>
              </operationHasOwnedParameters>
              <operationHasOwnedParameters>
                <parameter Id="72313c90-c9b7-4c46-a348-65140c7c5f52" direction="Return" isUnique="false">
                  <elementDefinition Id="afc30e31-1b9f-46dd-9d24-bd1086e8ad3e" />
                  <type_NamedElement>
                    <referencedTypeMoniker Id="6a45fed8-1689-4fa9-8e39-f876365db554" LastKnownName="bool" />
                  </type_NamedElement>
                </parameter>
              </operationHasOwnedParameters>
            </ownedParameters>
          </operation>
        </ownedOperationsInternal>
      </class>
    </logicalClassDesignerModelHasTypes>
    <logicalClassDesignerModelHasTypes>
      <class Id="eeea4536-adc9-431d-8cb2-7cad87e92193" name="SparePart" isAbstract="false" isLeaf="false" isActiveClass="false">
        <elementDefinition Id="3113cd22-0eb7-43e8-bafb-033a4008083a" />
        <ownedAttributesInternal>
          <property Id="969b11b7-7041-489d-9db1-adf48ec8b975" name="id" isLeaf="false" isStatic="false" isReadOnly="false" isUnique="false" isDerived="false" isDerivedUnion="false" aggregation="None" isComposite="false">
            <elementDefinition Id="69675266-0053-49d8-a27f-8e24b8333c32" />
            <type_NamedElement>
              <referencedTypeMoniker Id="bed62a32-5b87-4e40-9259-b99a5a7769a5" LastKnownName="Integer" />
            </type_NamedElement>
          </property>
          <property Id="318f4e95-45c7-4e61-b0fc-6139c8de4a71" name="Name" isLeaf="false" isStatic="false" isReadOnly="false" isUnique="false" isDerived="false" isDerivedUnion="false" aggregation="None" isComposite="false">
            <elementDefinition Id="425601e3-681e-4098-9838-08ad5e48c0ab" />
            <type_NamedElement>
              <referencedTypeMoniker Id="faf4849f-8756-4979-b0da-605e57790912" LastKnownName="String" />
            </type_NamedElement>
          </property>
          <property Id="3eec94bb-eca0-45a0-b49a-a1470160c86b" name="DelTime" isLeaf="false" isStatic="false" isReadOnly="false" isUnique="false" isDerived="false" isDerivedUnion="false" aggregation="None" isComposite="false">
            <elementDefinition Id="552a553a-8a6a-407a-a2ba-d6dc1fd28b6c" />
            <type_NamedElement>
              <referencedTypeMoniker Id="21f7cfc9-5064-4247-9d81-837d1a3d9114" LastKnownName="DateTime" />
            </type_NamedElement>
          </property>
          <property Id="1e6b4ddc-6eda-4e5a-975a-368a3f2bb4c9" name="ClientPrepayment" isLeaf="false" isStatic="false" isReadOnly="false" isUnique="false" isDerived="false" isDerivedUnion="false" aggregation="None" isComposite="false">
            <elementDefinition Id="bf716345-d5e1-4a54-a1cd-10754d384a10" />
            <type_NamedElement>
              <referencedTypeMoniker Id="d0e2218a-5be7-46cf-97a2-091e3a6a80e0" LastKnownName="decimal" />
            </type_NamedElement>
          </property>
        </ownedAttributesInternal>
        <ownedOperationsInternal>
          <operation Id="95ed0252-74df-42df-9c34-825f93248d3f" name="SparePart" isLeaf="false" isStatic="false" isAbstract="false" concurrency="Sequential" isQuery="false">
            <elementDefinition Id="27f0f21c-82e9-4f30-9b51-783ec9130038" />
            <ownedParameters>
              <operationHasOwnedParameters>
                <parameter Id="cfefff07-e7fe-4881-818a-e61ef917eca9" direction="Return" isUnique="false">
                  <elementDefinition Id="41410c35-c2c3-41ae-9783-c5fc10661e8c" />
                  <type_NamedElement>
                    <referencedTypeMoniker Id="62e1c591-1fc8-4d49-889d-ba3d80faa959" LastKnownName="void" />
                  </type_NamedElement>
                </parameter>
              </operationHasOwnedParameters>
            </ownedParameters>
          </operation>
          <operation Id="167bea8d-3431-451d-ac08-ccb887ee3890" name="AddSparePart" isLeaf="false" isStatic="false" isAbstract="false" concurrency="Sequential" isQuery="false">
            <elementDefinition Id="b09c9e8c-848d-4aa7-966e-7bf61ebca3d4" />
            <ownedParameters>
              <operationHasOwnedParameters>
                <parameter Id="e991a6d2-62f3-4018-8192-9b2c56532574" direction="Return" isUnique="false">
                  <elementDefinition Id="b54909ce-825e-4736-bb61-31acfa14cabc" />
                  <type_NamedElement>
                    <referencedTypeMoniker Id="6a45fed8-1689-4fa9-8e39-f876365db554" LastKnownName="bool" />
                  </type_NamedElement>
                </parameter>
              </operationHasOwnedParameters>
            </ownedParameters>
          </operation>
          <operation Id="1f046f80-5ced-4861-9738-60cda11e4217" name="DelSparePart" isLeaf="false" isStatic="false" isAbstract="false" concurrency="Sequential" isQuery="false">
            <elementDefinition Id="add74ebc-2899-4b3f-b3b6-aea18c6e5008" />
            <ownedParameters>
              <operationHasOwnedParameters>
                <parameter Id="cc685815-770d-4660-9d35-b85b15969186" direction="Return" isUnique="false">
                  <elementDefinition Id="962b949c-48df-441d-9942-5f421ae39f09" />
                  <type_NamedElement>
                    <referencedTypeMoniker Id="6a45fed8-1689-4fa9-8e39-f876365db554" LastKnownName="bool" />
                  </type_NamedElement>
                </parameter>
              </operationHasOwnedParameters>
            </ownedParameters>
          </operation>
          <operation Id="1ccc4db8-5bad-4adc-aff1-0c5fb20c9bcf" name="EditSparePart" isLeaf="false" isStatic="false" isAbstract="false" concurrency="Sequential" isQuery="false">
            <elementDefinition Id="97b72644-567a-4730-8a1b-4730e9552a41" />
            <ownedParameters>
              <operationHasOwnedParameters>
                <parameter Id="c8c98609-2877-479c-ad05-88c1b272a239" direction="Return" isUnique="false">
                  <elementDefinition Id="757e4570-2ca7-4331-a2df-4a032e9db628" />
                  <type_NamedElement>
                    <referencedTypeMoniker Id="6a45fed8-1689-4fa9-8e39-f876365db554" LastKnownName="bool" />
                  </type_NamedElement>
                </parameter>
              </operationHasOwnedParameters>
            </ownedParameters>
          </operation>
          <operation Id="9f98a337-6f6a-4d32-83d7-b5dc10285948" name="GetCountInStock" isLeaf="false" isStatic="false" isAbstract="false" concurrency="Sequential" isQuery="false">
            <elementDefinition Id="4277045d-cd2f-4635-8492-054f1f7eca0b" />
            <ownedParameters>
              <operationHasOwnedParameters>
                <parameter Id="738d164a-dcbe-44d8-8268-a4f3daa64ec3" name="Workshop" direction="In" isUnique="false">
                  <elementDefinition Id="d84fc354-c6c3-45ff-82e4-98d6d7e34371" />
                  <type_NamedElement>
                    <referencedTypeMoniker Id="f4c65483-48fa-48c6-b1ba-774306746da9" LastKnownName="Workshop" />
                  </type_NamedElement>
                </parameter>
              </operationHasOwnedParameters>
              <operationHasOwnedParameters>
                <parameter Id="200ad890-2462-41c5-bcde-b2d8204849e0" direction="Return" isUnique="false">
                  <elementDefinition Id="4e098037-db03-4dca-ba6b-d103a07f06cf" />
                  <type_NamedElement>
                    <referencedTypeMoniker Id="de578a74-cb65-4d29-833c-4c0b903c29db" LastKnownName="int" />
                  </type_NamedElement>
                </parameter>
              </operationHasOwnedParameters>
            </ownedParameters>
          </operation>
          <operation Id="e7c80f9e-78be-4837-a2de-5e747421b887" name="GetCountInTransit" isLeaf="false" isStatic="false" isAbstract="false" concurrency="Sequential" isQuery="false">
            <elementDefinition Id="21941057-ba68-484a-bb34-47568994bf0c" />
            <ownedParameters>
              <operationHasOwnedParameters>
                <parameter Id="ceeb65b1-5b05-4984-af8d-281637274558" name="Workshop" direction="In" isUnique="false">
                  <elementDefinition Id="0e53c483-32a1-488e-b999-77bf308bccc2" />
                  <type_NamedElement>
                    <referencedTypeMoniker Id="f4c65483-48fa-48c6-b1ba-774306746da9" LastKnownName="Workshop" />
                  </type_NamedElement>
                </parameter>
              </operationHasOwnedParameters>
              <operationHasOwnedParameters>
                <parameter Id="781cd734-d95d-4d3e-ac42-0e9a2fdfbe25" direction="Return" isUnique="false">
                  <elementDefinition Id="e2fed4e4-2a76-4a56-a4f3-2e15b2577f34" />
                  <type_NamedElement>
                    <referencedTypeMoniker Id="de578a74-cb65-4d29-833c-4c0b903c29db" LastKnownName="int" />
                  </type_NamedElement>
                </parameter>
              </operationHasOwnedParameters>
            </ownedParameters>
          </operation>
          <operation Id="520d3c12-6a24-482b-a167-b1f7ba9cbde5" name="GetCountInStock" isLeaf="false" isStatic="false" isAbstract="false" concurrency="Sequential" isQuery="false">
            <elementDefinition Id="ba3deaf2-9fa1-4bbe-a0fd-f1233eee5378" />
            <ownedParameters>
              <operationHasOwnedParameters>
                <parameter Id="f39cb652-5cbc-4d90-9bb1-c5e967036715" direction="Return" isUnique="false">
                  <elementDefinition Id="9c8436a8-8470-4eee-b7cf-079f681fbb00" />
                  <type_NamedElement>
                    <referencedTypeMoniker Id="de578a74-cb65-4d29-833c-4c0b903c29db" LastKnownName="int" />
                  </type_NamedElement>
                </parameter>
              </operationHasOwnedParameters>
            </ownedParameters>
          </operation>
          <operation Id="f2de0fa1-0a9e-47b2-aae5-f072cf9cb767" name="GetCountInTransit" isLeaf="false" isStatic="false" isAbstract="false" concurrency="Sequential" isQuery="false">
            <elementDefinition Id="cda7fadb-33d8-454c-9de2-dd67c9748ee7" />
            <ownedParameters>
              <operationHasOwnedParameters>
                <parameter Id="16f20bdc-23e8-45be-8a64-f1bb908f82f0" direction="Return" isUnique="false">
                  <elementDefinition Id="8066f667-a11d-4c41-a879-07ee7df3e57e" />
                  <type_NamedElement>
                    <referencedTypeMoniker Id="de578a74-cb65-4d29-833c-4c0b903c29db" LastKnownName="int" />
                  </type_NamedElement>
                </parameter>
              </operationHasOwnedParameters>
            </ownedParameters>
          </operation>
        </ownedOperationsInternal>
      </class>
    </logicalClassDesignerModelHasTypes>
    <packageHasNamedElement>
      <referencedType Id="df8dd8bd-98b9-4b9d-a18e-fcdb3b31fa72" name="SparePart" isAbstract="false" isLeaf="false" cachedFullName="CompServiceClassDiagram::SparePart">
        <elementDefinition Id="3113cd22-0eb7-43e8-bafb-033a4008083a" />
      </referencedType>
    </packageHasNamedElement>
    <packageHasNamedElement>
      <referencedType Id="08265551-2095-47de-bdb0-a7af11d7a3d7" name="List&lt;BatchSpareParts&gt;" isAbstract="false" isLeaf="false" cachedFullName="List&lt;BatchSpareParts&gt;">
        <elementDefinition Id="4dc11e33-1bec-4061-b2b1-4e6f90f82db7" />
      </referencedType>
    </packageHasNamedElement>
    <packageHasNamedElement>
      <referencedType Id="a983ce7e-a30b-442b-8780-478ad8636aaf" name="Batch" isAbstract="false" isLeaf="false" cachedFullName="CompServiceClassDiagram::Batch">
        <elementDefinition Id="1459b137-3ab1-49cb-b736-a72c4b00e2c5" />
      </referencedType>
    </packageHasNamedElement>
    <logicalClassDesignerModelHasTypes>
      <class Id="a06c805f-f547-4fea-92a6-54a522d9952b" name="BatchesList {static}" isAbstract="false" isLeaf="false" isActiveClass="false">
        <elementDefinition Id="0d0b60c1-0c8a-4586-a1db-45dcd256e7c0" />
        <targetEnds>
          <association Id="090bcaf5-da75-4e06-8c6a-a7d07c548771" isDerived="false" sourceEndRoleName="BatchSpareParts {static}" targetEndRoleName="Batch" isLeaf="false" isAbstract="false">
            <classMoniker Id="593cb2ed-8cab-400f-84d9-404853805b39" LastKnownName="Batch" />
            <relationshipOwnedElementsInternal>
              <associationHasOwnedEnds>
                <memberEnd Id="0735a3aa-2f9f-4130-9a9e-f666916458a4" name="BatchSpareParts {static}" isLeaf="false" isStatic="false" isReadOnly="false" isDerived="false" isDerivedUnion="false" aggregation="Shared" isComposite="false" isNavigableOwned="false">
                  <elementDefinition Id="d9bb70c7-f137-4b25-a928-41b46b4823b1" />
                </memberEnd>
              </associationHasOwnedEnds>
              <associationHasOwnedEnds>
                <memberEnd Id="2154e831-5054-49e2-b44f-96a98ac5deb6" name="Batch" isLeaf="false" isStatic="false" isReadOnly="false" isDerived="false" isDerivedUnion="false" aggregation="None" isComposite="false">
                  <lowerValueInternal>
                    <literalString Id="3e078259-5faf-4e7b-8c41-bcd95e46c860" name="Lower" value="1">
                      <elementDefinition Id="167da5e5-5dac-4b64-92d0-42e90560093b" />
                    </literalString>
                  </lowerValueInternal>
                  <upperValueInternal>
                    <literalString Id="7a9354c1-3e1d-4c61-8000-5f639a492c2b" name="Upper" value="*">
                      <elementDefinition Id="2217b4b1-a956-4668-865c-d29c89feb387" />
                    </literalString>
                  </upperValueInternal>
                  <elementDefinition Id="076f6404-fd44-4993-ba9e-9ef5198e8ab7" />
                </memberEnd>
              </associationHasOwnedEnds>
            </relationshipOwnedElementsInternal>
            <elementDefinition Id="bed92964-0c9e-4c6a-a2f3-e900511f9cc3" />
          </association>
        </targetEnds>
        <ownedOperationsInternal>
          <operation Id="b2372bdc-27e6-4383-8d03-6e254bca255b" name="GetBatches" isLeaf="false" isStatic="true" isAbstract="false" concurrency="Sequential" isQuery="false">
            <elementDefinition Id="18a9b79c-2e35-45b4-b8e2-1a527e445f3a" />
            <ownedParameters>
              <operationHasOwnedParameters>
                <parameter Id="cefe70fd-0fce-43b6-955f-4cc019c2d851" direction="Return" isUnique="false">
                  <elementDefinition Id="e6a1f1af-fc0b-463c-a8f9-8892ded480b8" />
                  <type_NamedElement>
                    <referencedTypeMoniker Id="633367a9-29cd-4262-a3a8-ae19491ebe33" LastKnownName="List&lt;Batch&gt;" />
                  </type_NamedElement>
                </parameter>
              </operationHasOwnedParameters>
              <operationHasOwnedParameters>
                <parameter Id="dcb0e09f-2914-4ed0-8d94-3fe236120929" name="desk" direction="In" isUnique="false">
                  <elementDefinition Id="99b25cd3-c614-4942-8f36-cc6b48af327d" />
                  <type_NamedElement>
                    <referencedTypeMoniker Id="6a45fed8-1689-4fa9-8e39-f876365db554" LastKnownName="bool" />
                  </type_NamedElement>
                </parameter>
              </operationHasOwnedParameters>
              <operationHasOwnedParameters>
                <parameter Id="40658f17-2909-4f88-b997-0403ed5799ae" name="sortBy" direction="In" isUnique="false">
                  <elementDefinition Id="8498dec9-3f25-4d17-a1d1-80aee953ba90" />
                  <type_NamedElement>
                    <referencedTypeMoniker Id="5432db89-8420-4f3f-bf54-d2b10dcc16ad" LastKnownName="string" />
                  </type_NamedElement>
                </parameter>
              </operationHasOwnedParameters>
              <operationHasOwnedParameters>
                <parameter Id="c7a18aba-f622-45aa-bf15-531b994f8711" name="filterA" direction="In" isUnique="false">
                  <elementDefinition Id="7396c840-30f3-4255-960b-7f648c0c053d" />
                  <type_NamedElement>
                    <referencedTypeMoniker Id="a983ce7e-a30b-442b-8780-478ad8636aaf" LastKnownName="Batch" />
                  </type_NamedElement>
                </parameter>
              </operationHasOwnedParameters>
              <operationHasOwnedParameters>
                <parameter Id="3ae7b1dc-5ae2-426f-aa0b-6656921e0472" name="filterB" direction="In" isUnique="false">
                  <elementDefinition Id="63c957e1-b7f8-4b4f-9f50-1515b72d6486" />
                  <type_NamedElement>
                    <referencedTypeMoniker Id="a983ce7e-a30b-442b-8780-478ad8636aaf" LastKnownName="Batch" />
                  </type_NamedElement>
                </parameter>
              </operationHasOwnedParameters>
              <operationHasOwnedParameters>
                <parameter Id="de573eec-ffe4-424c-a022-fc36f677aaa0" name="count" direction="In" isUnique="false">
                  <elementDefinition Id="69b18163-fa07-4ffd-bb05-c458ab75ac06" />
                  <type_NamedElement>
                    <referencedTypeMoniker Id="de578a74-cb65-4d29-833c-4c0b903c29db" LastKnownName="int" />
                  </type_NamedElement>
                </parameter>
              </operationHasOwnedParameters>
              <operationHasOwnedParameters>
                <parameter Id="c1623f6c-441d-4c5c-b968-fd7e25ea1f1d" name="page" direction="In" isUnique="false">
                  <elementDefinition Id="9b488707-d933-4057-a5fe-0e5ebb7d04a1" />
                  <type_NamedElement>
                    <referencedTypeMoniker Id="de578a74-cb65-4d29-833c-4c0b903c29db" LastKnownName="int" />
                  </type_NamedElement>
                </parameter>
              </operationHasOwnedParameters>
            </ownedParameters>
          </operation>
          <operation Id="a4ae0425-cc9b-4780-b030-28dbd1ad717d" name="GetById" isLeaf="false" isStatic="true" isAbstract="false" concurrency="Sequential" isQuery="false">
            <elementDefinition Id="db9c39dc-2b58-4722-a525-7eb6905aeb7d" />
            <ownedParameters>
              <operationHasOwnedParameters>
                <parameter Id="9fedcb1a-4b38-4d39-b06e-2f38523a58ae" name="Int" direction="In" isUnique="false">
                  <elementDefinition Id="3044c137-f782-4bc2-a824-0b2077a98cb5" />
                </parameter>
              </operationHasOwnedParameters>
              <operationHasOwnedParameters>
                <parameter Id="0cebb4cd-0029-4006-9733-174cabc096ca" direction="Return" isUnique="false">
                  <elementDefinition Id="b10bd59e-57ab-46b7-9250-85c598987bfc" />
                  <type_NamedElement>
                    <referencedTypeMoniker Id="a983ce7e-a30b-442b-8780-478ad8636aaf" LastKnownName="Batch" />
                  </type_NamedElement>
                </parameter>
              </operationHasOwnedParameters>
            </ownedParameters>
          </operation>
        </ownedOperationsInternal>
      </class>
    </logicalClassDesignerModelHasTypes>
    <logicalClassDesignerModelHasTypes>
      <class Id="42c69648-403a-439a-b2a6-1de3e7380d47" name="EmplyeesTimetablesList {static}" isAbstract="false" isLeaf="false" isActiveClass="false">
        <elementDefinition Id="2e52caa1-76e1-4d41-a6f9-0112993127e5" />
        <targetEnds>
          <association Id="61d76c84-3080-432f-b729-ca504efc9d84" isDerived="false" sourceEndRoleName="EmplyeesTimetablesList" targetEndRoleName="EmplyeeTimetable" isLeaf="false" isAbstract="false">
            <classMoniker Id="53066004-9395-4113-afdd-9a344a8c03d3" LastKnownName="EmplyeeTimetable" />
            <relationshipOwnedElementsInternal>
              <associationHasOwnedEnds>
                <memberEnd Id="bc949615-b4ed-4811-a217-79eb7e850937" name="EmplyeesTimetablesList" isLeaf="false" isStatic="false" isReadOnly="false" isDerived="false" isDerivedUnion="false" aggregation="Shared" isComposite="false" isNavigableOwned="false">
                  <elementDefinition Id="8cf8877d-aca9-4da1-b714-bd6df9814a7a" />
                </memberEnd>
              </associationHasOwnedEnds>
              <associationHasOwnedEnds>
                <memberEnd Id="452aa13f-5bc0-4224-be97-3352004a8574" name="EmplyeeTimetable" isLeaf="false" isStatic="false" isReadOnly="false" isDerived="false" isDerivedUnion="false" aggregation="None" isComposite="false">
                  <lowerValueInternal>
                    <literalString Id="f000c5f7-a229-4bba-9244-47b37be30dae" name="Lower" value="1">
                      <elementDefinition Id="591cd968-b714-495b-8eed-8aeaff7c71ea" />
                    </literalString>
                  </lowerValueInternal>
                  <upperValueInternal>
                    <literalString Id="8d6d8a44-8841-4e56-b06f-3e53587e6519" name="Upper" value="*">
                      <elementDefinition Id="83481481-09ed-4d9d-9c78-0ffc4e8d5f59" />
                    </literalString>
                  </upperValueInternal>
                  <elementDefinition Id="4d50c4c2-386a-453f-ac5d-a202552b9deb" />
                </memberEnd>
              </associationHasOwnedEnds>
            </relationshipOwnedElementsInternal>
            <elementDefinition Id="ea8180e9-d8b2-4fa8-9264-42c4fccfc142" />
          </association>
        </targetEnds>
        <ownedOperationsInternal>
          <operation Id="31fa462b-1512-414b-a908-eda547a6d279" name="GetById" isLeaf="false" isStatic="true" isAbstract="false" concurrency="Sequential" isQuery="false">
            <elementDefinition Id="432288a1-5087-4877-9444-fd0dc3c78874" />
            <ownedParameters>
              <operationHasOwnedParameters>
                <parameter Id="2096dd0f-782f-4afd-9992-9f093a5b04ff" name="Int" direction="In" isUnique="false">
                  <elementDefinition Id="1ec315d7-ff4a-4293-ae94-286f749dbdbe" />
                </parameter>
              </operationHasOwnedParameters>
              <operationHasOwnedParameters>
                <parameter Id="135dbb73-171c-4574-9c7d-b4a6f480d8e9" direction="Return" isUnique="false">
                  <elementDefinition Id="bf7ebf6c-b01a-412c-b9d4-c344eb1bc5e7" />
                  <type_NamedElement>
                    <referencedTypeMoniker Id="71b933ea-7489-4e1c-8c74-7c5423e0afc1" LastKnownName="EmployeeTimetable" />
                  </type_NamedElement>
                </parameter>
              </operationHasOwnedParameters>
            </ownedParameters>
          </operation>
        </ownedOperationsInternal>
      </class>
    </logicalClassDesignerModelHasTypes>
    <logicalClassDesignerModelHasTypes>
      <class Id="69fd5825-5617-4e58-ad0a-fced4ca348db" name="RolesList {static}" isAbstract="false" isLeaf="false" isActiveClass="false">
        <elementDefinition Id="42ddfc52-fbb8-475f-9c31-7c1b40824a23" />
        <targetEnds>
          <association Id="6d5a9f74-6327-4b47-ae4d-ef9e0fa87331" isDerived="false" sourceEndRoleName="RolesList" targetEndRoleName="Role" isLeaf="false" isAbstract="false">
            <classMoniker Id="49e29943-c54c-45f2-9af3-97e7397fbc62" LastKnownName="Role" />
            <relationshipOwnedElementsInternal>
              <associationHasOwnedEnds>
                <memberEnd Id="766d4500-ade0-4cf3-b076-a7d1e01c1298" name="RolesList" isLeaf="false" isStatic="false" isReadOnly="false" isDerived="false" isDerivedUnion="false" aggregation="Shared" isComposite="false" isNavigableOwned="false">
                  <elementDefinition Id="1c448ecc-a3a5-44e8-bf11-879952d270fe" />
                </memberEnd>
              </associationHasOwnedEnds>
              <associationHasOwnedEnds>
                <memberEnd Id="2c553c0f-3060-4979-9a46-262b613086fb" name="Role" isLeaf="false" isStatic="false" isReadOnly="false" isDerived="false" isDerivedUnion="false" aggregation="None" isComposite="false">
                  <lowerValueInternal>
                    <literalString Id="47714316-858c-46ad-a1e2-8a7d0450a63d" name="Lower" value="1">
                      <elementDefinition Id="6543986d-4a76-4c61-a8a2-62e838fc2412" />
                    </literalString>
                  </lowerValueInternal>
                  <upperValueInternal>
                    <literalString Id="8e3e53d7-e257-49a8-bb51-303629d197e4" name="Upper" value="*">
                      <elementDefinition Id="f1cd5209-9065-4e14-9b8d-f9a8adf0b165" />
                    </literalString>
                  </upperValueInternal>
                  <elementDefinition Id="4f0a32f5-4afb-4a1e-a97d-b38745790497" />
                </memberEnd>
              </associationHasOwnedEnds>
            </relationshipOwnedElementsInternal>
            <elementDefinition Id="70a5b1ff-9623-4e6a-b967-99a123da72ef" />
          </association>
        </targetEnds>
        <ownedOperationsInternal>
          <operation Id="c49d77d1-35b4-4107-aad3-da860619543e" name="GetRoles" isLeaf="false" isStatic="true" isAbstract="false" concurrency="Sequential" isQuery="false">
            <elementDefinition Id="f99edb53-2e29-4575-970e-60011a8448f3" />
            <ownedParameters>
              <operationHasOwnedParameters>
                <parameter Id="1758543c-fd6d-4890-bf08-0fc3dd999768" direction="Return" isUnique="false">
                  <elementDefinition Id="6e2bbd12-8e15-4c1e-ab46-4ea2fe4ccb33" />
                  <type_NamedElement>
                    <referencedTypeMoniker Id="ab321961-cca2-4429-9042-0eb2fa38c01b" LastKnownName="List&lt;Role&gt;" />
                  </type_NamedElement>
                </parameter>
              </operationHasOwnedParameters>
              <operationHasOwnedParameters>
                <parameter Id="b8f4c552-a816-4e2d-aacb-47c4748338fa" name="filterA" direction="In" isUnique="false">
                  <elementDefinition Id="bc09e2dd-3d33-4fab-9365-47a0e6126a7a" />
                  <type_NamedElement>
                    <referencedTypeMoniker Id="dcabf460-1745-43b0-bd60-733bb6dd04c2" LastKnownName="Role" />
                  </type_NamedElement>
                </parameter>
              </operationHasOwnedParameters>
              <operationHasOwnedParameters>
                <parameter Id="4f68d9a0-7f0e-4a36-b03b-f1a4b11bd4eb" name="sortBy" direction="In" isUnique="false">
                  <elementDefinition Id="8ad13f4f-f38b-447f-8f12-9fc4bb6e94b8" />
                  <type_NamedElement>
                    <referencedTypeMoniker Id="5432db89-8420-4f3f-bf54-d2b10dcc16ad" LastKnownName="string" />
                  </type_NamedElement>
                </parameter>
              </operationHasOwnedParameters>
              <operationHasOwnedParameters>
                <parameter Id="6fe7d43e-4eb6-4bf3-860e-c86d8fd44e1d" name="employee" direction="In" isUnique="false">
                  <elementDefinition Id="4ebf081f-1f8f-4ecd-98e8-734f01a1d940" />
                  <type_NamedElement>
                    <referencedTypeMoniker Id="448d814c-c87b-42ed-9f0f-59cb5e5b0d67" LastKnownName="Employee" />
                  </type_NamedElement>
                </parameter>
              </operationHasOwnedParameters>
              <operationHasOwnedParameters>
                <parameter Id="c4d008c8-0bb6-4a9e-9dde-e56771c2100a" name="desk" direction="In" isUnique="false">
                  <elementDefinition Id="a9418ca7-76b7-4d18-be1d-48024689e8d4" />
                  <type_NamedElement>
                    <referencedTypeMoniker Id="6a45fed8-1689-4fa9-8e39-f876365db554" LastKnownName="bool" />
                  </type_NamedElement>
                </parameter>
              </operationHasOwnedParameters>
              <operationHasOwnedParameters>
                <parameter Id="26718e44-77d4-432d-b0af-220cc7e199c5" name="count" direction="In" isUnique="false">
                  <elementDefinition Id="dcff6d33-ec03-4417-ae31-9a10d50f55b1" />
                  <type_NamedElement>
                    <referencedTypeMoniker Id="de578a74-cb65-4d29-833c-4c0b903c29db" LastKnownName="int" />
                  </type_NamedElement>
                </parameter>
              </operationHasOwnedParameters>
              <operationHasOwnedParameters>
                <parameter Id="7999eae5-2ba9-4e86-bd10-8ed8d0112e45" name="page" direction="In" isUnique="false">
                  <elementDefinition Id="2e1f7da1-301d-4845-92a3-f6f214a0f0e3" />
                  <type_NamedElement>
                    <referencedTypeMoniker Id="de578a74-cb65-4d29-833c-4c0b903c29db" LastKnownName="int" />
                  </type_NamedElement>
                </parameter>
              </operationHasOwnedParameters>
            </ownedParameters>
          </operation>
          <operation Id="becbd85e-4964-4d02-8dba-1de0e308ba05" name="GetById" isLeaf="false" isStatic="true" isAbstract="false" concurrency="Sequential" isQuery="false">
            <elementDefinition Id="041f500b-9656-470b-b5a6-e0283938ca2e" />
            <ownedParameters>
              <operationHasOwnedParameters>
                <parameter Id="98d73b36-67df-4218-8e4e-c85621041bce" name="Int" direction="In" isUnique="false">
                  <elementDefinition Id="1cdc831c-f0f8-4541-9491-c4ee92d9f3c6" />
                </parameter>
              </operationHasOwnedParameters>
              <operationHasOwnedParameters>
                <parameter Id="b5d08d0e-7cca-44c9-b15a-6fcc36aab2c4" direction="Return" isUnique="false">
                  <elementDefinition Id="c50c599d-ef0f-46bd-9a36-1cc9a21d9c53" />
                  <type_NamedElement>
                    <referencedTypeMoniker Id="dcabf460-1745-43b0-bd60-733bb6dd04c2" LastKnownName="Role" />
                  </type_NamedElement>
                </parameter>
              </operationHasOwnedParameters>
            </ownedParameters>
          </operation>
        </ownedOperationsInternal>
      </class>
    </logicalClassDesignerModelHasTypes>
    <packageHasNamedElement>
      <referencedType Id="ab321961-cca2-4429-9042-0eb2fa38c01b" name="List&lt;Role&gt;" isAbstract="false" isLeaf="false" cachedFullName="List&lt;Role&gt;">
        <elementDefinition Id="d1db932f-72fa-43dd-9cc4-530bdcc87b37" />
      </referencedType>
    </packageHasNamedElement>
    <packageHasNamedElement>
      <referencedType Id="add70660-4fab-48a9-bb58-4ca4337c1763" name="int" isAbstract="false" isLeaf="false" cachedFullName="int">
        <elementDefinition Id="f984419c-cfc8-4466-a4ac-951b45074e3f" />
      </referencedType>
    </packageHasNamedElement>
    <logicalClassDesignerModelHasTypes>
      <class Id="af724895-87f7-4c5d-8a00-c77e8952fb32" name="WorkshopsTimetablesList {static}" isAbstract="false" isLeaf="false" isActiveClass="false">
        <elementDefinition Id="f915b3eb-75b5-45f4-b409-5b80e3768efb" />
        <targetEnds>
          <association Id="dd3af246-530f-4b58-92e7-8c342b1bd470" isDerived="false" sourceEndRoleName="WorkshopsTimetablesList" targetEndRoleName="WorkshopTimetable" isLeaf="false" isAbstract="false">
            <classMoniker Id="571d2f84-3da1-4c3f-a2e4-9b8d443c215c" LastKnownName="WorkshopTimetable" />
            <relationshipOwnedElementsInternal>
              <associationHasOwnedEnds>
                <memberEnd Id="c8d9b7eb-f25f-4d43-b5c8-c32c2df59678" name="WorkshopsTimetablesList" isLeaf="false" isStatic="false" isReadOnly="false" isDerived="false" isDerivedUnion="false" aggregation="Shared" isComposite="false" isNavigableOwned="false">
                  <elementDefinition Id="993b8989-3b20-47e6-9cfb-f85e5db5b7d3" />
                </memberEnd>
              </associationHasOwnedEnds>
              <associationHasOwnedEnds>
                <memberEnd Id="601b7af4-d21e-4886-b67d-41dac959b383" name="WorkshopTimetable" isLeaf="false" isStatic="false" isReadOnly="false" isDerived="false" isDerivedUnion="false" aggregation="None" isComposite="false">
                  <lowerValueInternal>
                    <literalString Id="937104d3-75b5-436e-a592-6c635fcb3c2a" name="Lower" value="1">
                      <elementDefinition Id="f15bf275-0765-46e9-a0e9-781c72a3b0fb" />
                    </literalString>
                  </lowerValueInternal>
                  <upperValueInternal>
                    <literalString Id="da8e5aab-f71c-48b8-8c2f-41a3db9c86db" name="Upper" value="*">
                      <elementDefinition Id="debd0293-ed30-4e14-bfec-234b10cbfcf1" />
                    </literalString>
                  </upperValueInternal>
                  <elementDefinition Id="e4ead5dd-a7a0-488c-89a5-b06ec9baafee" />
                </memberEnd>
              </associationHasOwnedEnds>
            </relationshipOwnedElementsInternal>
            <elementDefinition Id="193dd42f-d121-46cf-b8c7-6224a0c7c45e" />
          </association>
        </targetEnds>
        <ownedOperationsInternal>
          <operation Id="1888afee-decc-4801-8354-968eaa6d8ce8" name="GetTimetables" isLeaf="false" isStatic="true" isAbstract="false" concurrency="Sequential" isQuery="false">
            <elementDefinition Id="d40ef556-fb57-4cbb-8c5c-67416a4599e0" />
            <ownedParameters>
              <operationHasOwnedParameters>
                <parameter Id="62290085-563c-4171-95fc-2f74f978b6f5" direction="Return" isUnique="false">
                  <elementDefinition Id="21379757-d983-47c4-8dd0-f5f693f05e27" />
                  <type_NamedElement>
                    <referencedTypeMoniker Id="a504101a-fcd4-4855-ab99-405c7225b8c5" LastKnownName="List&lt;WorkshopTimetable&gt;" />
                  </type_NamedElement>
                </parameter>
              </operationHasOwnedParameters>
              <operationHasOwnedParameters>
                <parameter Id="0e461c82-b6e9-4620-9c70-1ccda94ef314" name="filterA" direction="In" isUnique="false">
                  <elementDefinition Id="f7fe30c6-8d04-451d-85e3-add12a00a27b" />
                  <type_NamedElement>
                    <referencedTypeMoniker Id="04c69843-b4ee-48ec-984a-fbaa08a042e5" LastKnownName="WorkshopTimetable" />
                  </type_NamedElement>
                </parameter>
              </operationHasOwnedParameters>
              <operationHasOwnedParameters>
                <parameter Id="09ffcccf-af97-4485-a4a8-34b841954b39" name="count" direction="In" isUnique="false">
                  <elementDefinition Id="43cd0103-772a-4ce7-a42d-67a334a42d1b" />
                  <type_NamedElement>
                    <referencedTypeMoniker Id="add70660-4fab-48a9-bb58-4ca4337c1763" LastKnownName="int" />
                  </type_NamedElement>
                </parameter>
              </operationHasOwnedParameters>
              <operationHasOwnedParameters>
                <parameter Id="7391cf70-048f-4856-a1fe-bdd7894f5686" name="page" direction="In" isUnique="false">
                  <elementDefinition Id="a2cf1711-9094-4b73-acc7-451475a96200" />
                  <type_NamedElement>
                    <referencedTypeMoniker Id="de578a74-cb65-4d29-833c-4c0b903c29db" LastKnownName="int" />
                  </type_NamedElement>
                </parameter>
              </operationHasOwnedParameters>
            </ownedParameters>
          </operation>
          <operation Id="83108ecf-547e-4897-aa13-c113e8951bdc" name="GetById" isLeaf="false" isStatic="true" isAbstract="false" concurrency="Sequential" isQuery="false">
            <elementDefinition Id="742e792d-8caa-418d-b7a7-294b5d957f4f" />
            <ownedParameters>
              <operationHasOwnedParameters>
                <parameter Id="8b095f6a-fad5-4771-a241-5c1a3ec2df79" direction="Return" isUnique="false">
                  <elementDefinition Id="55569763-ab40-4e88-a257-8ce1f937ac54" />
                  <type_NamedElement>
                    <referencedTypeMoniker Id="04c69843-b4ee-48ec-984a-fbaa08a042e5" LastKnownName="WorkshopTimetable" />
                  </type_NamedElement>
                </parameter>
              </operationHasOwnedParameters>
              <operationHasOwnedParameters>
                <parameter Id="b253f914-59f9-4003-8597-a7dc886a1343" name="Int" direction="In" isUnique="false">
                  <elementDefinition Id="39ec7ffd-82b7-43ed-8721-c34ac0e1d956" />
                </parameter>
              </operationHasOwnedParameters>
            </ownedParameters>
          </operation>
        </ownedOperationsInternal>
      </class>
    </logicalClassDesignerModelHasTypes>
    <logicalClassDesignerModelHasTypes>
      <class Id="95359813-c357-418f-8e20-9e449af70436" name="Visit" isAbstract="false" isLeaf="false" isActiveClass="false">
        <elementDefinition Id="9993dc90-d853-4bfa-aa0b-1ad4db065e73" />
        <targetEnds>
          <association Id="8a208865-e0aa-4d9a-ba26-0faefe66d75d" isDerived="false" sourceEndRoleName="Visit" targetEndRoleName="OrderAtHome" isLeaf="false" isAbstract="false">
            <classMoniker Id="fefe1ea9-9a37-4d61-ab20-fdb71f38d1b3" LastKnownName="OrderAtHome" />
            <relationshipOwnedElementsInternal>
              <associationHasOwnedEnds>
                <memberEnd Id="4110e1b1-194a-4235-93ab-5b7750103f76" name="Visit" isLeaf="false" isStatic="false" isReadOnly="false" isDerived="false" isDerivedUnion="false" aggregation="Composite" isComposite="false" isNavigableOwned="false">
                  <lowerValueInternal>
                    <literalString Id="161d3b87-9069-4ef6-ae26-7c0de4d41819" name="Lower" value="1">
                      <elementDefinition Id="dbbc7e81-f1af-410c-90dc-1dc94616b2ac" />
                    </literalString>
                  </lowerValueInternal>
                  <upperValueInternal>
                    <literalString Id="3b19056d-2f5d-4373-823f-3991c4e99c82" name="Upper" value="*">
                      <elementDefinition Id="85fc4a8f-a152-4076-b073-0660e3eea1db" />
                    </literalString>
                  </upperValueInternal>
                  <elementDefinition Id="5bd8f9cf-6b41-440b-b1fa-78589b38dc58" />
                </memberEnd>
              </associationHasOwnedEnds>
              <associationHasOwnedEnds>
                <memberEnd Id="87dd2e1d-5ee2-4ea4-8144-d36cc1eededf" name="OrderAtHome" isLeaf="false" isStatic="false" isReadOnly="false" isDerived="false" isDerivedUnion="false" aggregation="None" isComposite="true">
                  <elementDefinition Id="ab000c32-afac-4e07-b093-ad95e81d42f6" />
                </memberEnd>
              </associationHasOwnedEnds>
            </relationshipOwnedElementsInternal>
            <elementDefinition Id="333fd19e-4fd3-4797-96c8-cacf8db390b8" />
          </association>
        </targetEnds>
        <ownedAttributesInternal>
          <property Id="914f54d4-4f2e-4578-a7f9-138ca035ce95" name="id" isLeaf="false" isStatic="false" isReadOnly="false" isUnique="false" isDerived="false" isDerivedUnion="false" aggregation="None" isComposite="false">
            <elementDefinition Id="bc5776f6-9341-4938-a4e4-3d14e57e4d23" />
            <type_NamedElement>
              <referencedTypeMoniker Id="bed62a32-5b87-4e40-9259-b99a5a7769a5" LastKnownName="Integer" />
            </type_NamedElement>
          </property>
          <property Id="dadc0743-ed81-4667-aa9a-24455724d8fb" name="DateVisit" isLeaf="false" isStatic="false" isReadOnly="false" isUnique="false" isDerived="false" isDerivedUnion="false" aggregation="None" isComposite="false">
            <elementDefinition Id="89d90fda-6851-408e-8576-7f9bf492bdae" />
            <type_NamedElement>
              <referencedTypeMoniker Id="f8fa7e64-5d47-4185-9119-20c7b0ef1db1" LastKnownName="DateTime" />
            </type_NamedElement>
          </property>
          <property Id="13928759-5f26-4784-876d-f2b80371d444" name="Order" isLeaf="false" isStatic="false" isReadOnly="false" isUnique="false" isDerived="false" isDerivedUnion="false" aggregation="None" isComposite="false">
            <elementDefinition Id="d528c99e-ec88-427e-b98e-77b73f850c0e" />
            <type_NamedElement>
              <referencedTypeMoniker Id="2003ed98-f3fa-4914-b435-1ab35dccca81" LastKnownName="OrderAtHome" />
            </type_NamedElement>
          </property>
          <property Id="b59a39e5-f197-4d24-828f-74597b907992" name="DelTime" isLeaf="false" isStatic="false" isReadOnly="false" isUnique="false" isDerived="false" isDerivedUnion="false" aggregation="None" isComposite="false">
            <elementDefinition Id="704742c6-64a7-48ea-af99-45479da9db04" />
            <type_NamedElement>
              <referencedTypeMoniker Id="5e95a766-896f-41c7-8951-778ddf708d7a" LastKnownName="DateTime" />
            </type_NamedElement>
          </property>
          <property Id="acbc5ebc-fd24-4ff3-b6b8-7723a07999a3" name="Done" isLeaf="false" isStatic="false" isReadOnly="false" isUnique="false" isDerived="false" isDerivedUnion="false" aggregation="None" isComposite="false">
            <elementDefinition Id="b17594fc-ce1e-41b8-a228-ac3bb3e91e17" />
            <type_NamedElement>
              <referencedTypeMoniker Id="6a45fed8-1689-4fa9-8e39-f876365db554" LastKnownName="bool" />
            </type_NamedElement>
          </property>
          <property Id="19879eaa-2ee4-4a15-b4c6-69d017a9e790" name="MasterComment" isLeaf="false" isStatic="false" isReadOnly="false" isUnique="false" isDerived="false" isDerivedUnion="false" aggregation="None" isComposite="false">
            <elementDefinition Id="fb347c8c-f23b-40c4-bbb4-4de68ac5f6ab" />
            <type_NamedElement>
              <referencedTypeMoniker Id="faf4849f-8756-4979-b0da-605e57790912" LastKnownName="String" />
            </type_NamedElement>
          </property>
        </ownedAttributesInternal>
        <ownedOperationsInternal>
          <operation Id="d1e3204c-b6a0-43e5-b39e-0aabceb183ee" name="Visit" isLeaf="false" isStatic="false" isAbstract="false" concurrency="Sequential" isQuery="false">
            <elementDefinition Id="da969982-b158-4560-809b-bfdf84344076" />
            <ownedParameters>
              <operationHasOwnedParameters>
                <parameter Id="88ec9f11-3e92-4188-87bc-0323c457423b" direction="Return" isUnique="false">
                  <elementDefinition Id="8958ecdc-d3ff-40cc-a051-dd13b45b27c0" />
                  <type_NamedElement>
                    <referencedTypeMoniker Id="62e1c591-1fc8-4d49-889d-ba3d80faa959" LastKnownName="void" />
                  </type_NamedElement>
                </parameter>
              </operationHasOwnedParameters>
            </ownedParameters>
          </operation>
          <operation Id="581e0bad-9703-46f0-9a34-1af3d55771b3" name="AddVisit" isLeaf="false" isStatic="false" isAbstract="false" concurrency="Sequential" isQuery="false">
            <elementDefinition Id="93696c68-a673-43d2-ba41-0de0ecbdb84d" />
            <ownedParameters>
              <operationHasOwnedParameters>
                <parameter Id="24d9d1eb-435a-41bb-9c5c-a848fc6e7bd3" direction="Return" isUnique="false">
                  <elementDefinition Id="e112c33f-e7c0-43c7-86d5-b19837dc0026" />
                  <type_NamedElement>
                    <referencedTypeMoniker Id="6a45fed8-1689-4fa9-8e39-f876365db554" LastKnownName="bool" />
                  </type_NamedElement>
                </parameter>
              </operationHasOwnedParameters>
            </ownedParameters>
          </operation>
          <operation Id="648c0d58-aa09-4f46-8930-f8af896745ad" name="DelVisit" isLeaf="false" isStatic="false" isAbstract="false" concurrency="Sequential" isQuery="false">
            <elementDefinition Id="4e9f417f-b8be-4c31-a70b-cb5c12baeb67" />
            <ownedParameters>
              <operationHasOwnedParameters>
                <parameter Id="683ea702-5b71-428f-a069-078cda642672" direction="Return" isUnique="false">
                  <elementDefinition Id="cc75c7aa-aa72-48b6-aa74-d62af7e1c2d9" />
                  <type_NamedElement>
                    <referencedTypeMoniker Id="6a45fed8-1689-4fa9-8e39-f876365db554" LastKnownName="bool" />
                  </type_NamedElement>
                </parameter>
              </operationHasOwnedParameters>
            </ownedParameters>
          </operation>
          <operation Id="4a6496e8-3c6e-4711-9eef-054122fee892" name="EditVisit" isLeaf="false" isStatic="false" isAbstract="false" concurrency="Sequential" isQuery="false">
            <elementDefinition Id="a8df466a-f926-4f27-a6c1-16d064c56217" />
            <ownedParameters>
              <operationHasOwnedParameters>
                <parameter Id="06760025-482a-4e8e-850b-49cb08c857e9" direction="Return" isUnique="false">
                  <elementDefinition Id="b9b0b9a9-aa4f-44f3-a5fa-27ccbd17c07f" />
                  <type_NamedElement>
                    <referencedTypeMoniker Id="6a45fed8-1689-4fa9-8e39-f876365db554" LastKnownName="bool" />
                  </type_NamedElement>
                </parameter>
              </operationHasOwnedParameters>
            </ownedParameters>
          </operation>
          <operation Id="94abda61-5bc7-429a-9609-d9cb5e4bd932" name="CalcEstimatedTime" isLeaf="false" isStatic="false" isAbstract="false" concurrency="Sequential" isQuery="false">
            <elementDefinition Id="54b09c59-4d69-4423-88e6-8d3525321348" />
            <ownedParameters>
              <operationHasOwnedParameters>
                <parameter Id="4709aef5-c18f-406f-88b3-5fbf652900fe" direction="Return" isUnique="false">
                  <elementDefinition Id="e93d3d2a-47e4-4375-9bff-2fb7d94266a4" />
                  <type_NamedElement>
                    <referencedTypeMoniker Id="afc7744e-e803-437f-814c-175324a339fb" LastKnownName="TimeSpan" />
                  </type_NamedElement>
                </parameter>
              </operationHasOwnedParameters>
            </ownedParameters>
          </operation>
          <operation Id="5f00ca06-a87c-4b3e-b1f7-30fd2baa122e" name="AddService" isLeaf="false" isStatic="false" isAbstract="false" concurrency="Sequential" isQuery="false">
            <elementDefinition Id="42bf5465-2ffe-479a-bd77-554eec86a340" />
            <ownedParameters>
              <operationHasOwnedParameters>
                <parameter Id="19b586c5-0fc7-4fca-8fdf-44020f0997aa" name="service" direction="In" isUnique="false">
                  <elementDefinition Id="19b1702e-af51-4c86-9630-f27e5ff1a17c" />
                  <type_NamedElement>
                    <referencedTypeMoniker Id="9366a8a0-2c9f-4aeb-81b2-7a52156b3689" LastKnownName="Service" />
                  </type_NamedElement>
                </parameter>
              </operationHasOwnedParameters>
              <operationHasOwnedParameters>
                <parameter Id="44c70951-fb24-4675-b68a-ed6ed9ea0470" direction="Return" isUnique="false">
                  <elementDefinition Id="1f1a548e-4d00-4852-9551-8c8d76d17dcd" />
                  <type_NamedElement>
                    <referencedTypeMoniker Id="6a45fed8-1689-4fa9-8e39-f876365db554" LastKnownName="bool" />
                  </type_NamedElement>
                </parameter>
              </operationHasOwnedParameters>
            </ownedParameters>
          </operation>
          <operation Id="6e4a1197-4019-4eb9-9691-3eec64d433f2" name="DelService" isLeaf="false" isStatic="false" isAbstract="false" concurrency="Sequential" isQuery="false">
            <elementDefinition Id="36b57778-4adb-4d82-84d7-47a510b7f8e0" />
            <ownedParameters>
              <operationHasOwnedParameters>
                <parameter Id="58f74b71-ebe6-4fae-8d36-6f0a0c57eb79" name="service" direction="In" isUnique="false">
                  <elementDefinition Id="e1e77097-9897-4ee0-a541-90f1fb91c289" />
                  <type_NamedElement>
                    <referencedTypeMoniker Id="9366a8a0-2c9f-4aeb-81b2-7a52156b3689" LastKnownName="Service" />
                  </type_NamedElement>
                </parameter>
              </operationHasOwnedParameters>
              <operationHasOwnedParameters>
                <parameter Id="fa26f2e2-1de9-4a98-b6ff-ca7ae9f962b2" direction="Return" isUnique="false">
                  <elementDefinition Id="b1bfa244-db7b-4791-8758-7f27509e6324" />
                  <type_NamedElement>
                    <referencedTypeMoniker Id="6a45fed8-1689-4fa9-8e39-f876365db554" LastKnownName="bool" />
                  </type_NamedElement>
                </parameter>
              </operationHasOwnedParameters>
            </ownedParameters>
          </operation>
          <operation Id="46d0613a-7cdc-44ab-bbf7-206e622aef50" name="CheckService" isLeaf="false" isStatic="false" isAbstract="false" concurrency="Sequential" isQuery="false">
            <elementDefinition Id="f8041b70-c1f5-4cff-9a61-46d39dcdde49" />
            <ownedParameters>
              <operationHasOwnedParameters>
                <parameter Id="05b7700d-3479-4cd0-8b4a-bb3bab7119a7" name="service" direction="In" isUnique="false">
                  <elementDefinition Id="8c4fc845-a44d-44c7-b622-c5a92d94c6cf" />
                  <type_NamedElement>
                    <referencedTypeMoniker Id="9366a8a0-2c9f-4aeb-81b2-7a52156b3689" LastKnownName="Service" />
                  </type_NamedElement>
                </parameter>
              </operationHasOwnedParameters>
              <operationHasOwnedParameters>
                <parameter Id="6cef5519-8782-481e-887c-5312df614a6d" direction="Return" isUnique="false">
                  <elementDefinition Id="20407fbc-701c-45b3-9b88-aa17d79dc8ec" />
                  <type_NamedElement>
                    <referencedTypeMoniker Id="6a45fed8-1689-4fa9-8e39-f876365db554" LastKnownName="bool" />
                  </type_NamedElement>
                </parameter>
              </operationHasOwnedParameters>
            </ownedParameters>
          </operation>
          <operation Id="1a75ddf9-2c05-4cbf-a4ed-2f6967c21106" name="GetVisitOrderServices" isLeaf="false" isStatic="false" isAbstract="false" concurrency="Sequential" isQuery="false">
            <elementDefinition Id="1c90e31c-cb90-4110-96fa-934196c5434d" />
            <ownedParameters>
              <operationHasOwnedParameters>
                <parameter Id="1364a677-297b-4b2b-8404-c42120c5008c" direction="Return" isUnique="false">
                  <elementDefinition Id="4a66ced2-3b1e-4fb3-b056-8dbc36ba309a" />
                  <type_NamedElement>
                    <referencedTypeMoniker Id="40f2070a-05f1-43ed-9aee-d973f659ad92" LastKnownName="List&lt;OrderService&gt;" />
                  </type_NamedElement>
                </parameter>
              </operationHasOwnedParameters>
            </ownedParameters>
          </operation>
        </ownedOperationsInternal>
      </class>
    </logicalClassDesignerModelHasTypes>
    <packageHasNamedElement>
      <referencedType Id="b0b17692-ed70-44cf-ac5b-99a01cf9a1e6" name="List&lt;Visit&gt;" isAbstract="false" isLeaf="false" cachedFullName="List&lt;Visit&gt;">
        <elementDefinition Id="5eac4f5b-f9fd-4c3c-96db-c22ef3c28240" />
      </referencedType>
    </packageHasNamedElement>
    <logicalClassDesignerModelHasTypes>
      <class Id="98a9030e-f073-473d-84df-aa4bd8b7fca2" name="VisitsList {static}" isAbstract="false" isLeaf="false" isActiveClass="false">
        <elementDefinition Id="1006174c-89b6-4aaa-add5-373fb3c386a5" />
        <targetEnds>
          <association Id="6caeadbe-b10a-4bd7-998a-e52679209239" isDerived="false" sourceEndRoleName="VisitsList {static}" targetEndRoleName="Visit" isLeaf="false" isAbstract="false">
            <classMoniker Id="95359813-c357-418f-8e20-9e449af70436" LastKnownName="Visit" />
            <relationshipOwnedElementsInternal>
              <associationHasOwnedEnds>
                <memberEnd Id="54d75070-d5d2-4a6b-8331-3871c54cd1ab" name="VisitsList {static}" isLeaf="false" isStatic="false" isReadOnly="false" isDerived="false" isDerivedUnion="false" aggregation="Shared" isComposite="false" isNavigableOwned="false">
                  <elementDefinition Id="5041ddc7-f9db-4c7e-b49e-b2cf07d5c342" />
                </memberEnd>
              </associationHasOwnedEnds>
              <associationHasOwnedEnds>
                <memberEnd Id="935c0202-db8f-4f60-8739-059607e1c647" name="Visit" isLeaf="false" isStatic="false" isReadOnly="false" isDerived="false" isDerivedUnion="false" aggregation="None" isComposite="false">
                  <elementDefinition Id="5a63b0e1-ed3e-47f6-8705-13bee9931f86" />
                </memberEnd>
              </associationHasOwnedEnds>
            </relationshipOwnedElementsInternal>
            <elementDefinition Id="54aea7d4-72e2-4692-9195-e58f51a14a78" />
          </association>
        </targetEnds>
        <ownedOperationsInternal>
          <operation Id="1146f852-e49d-4126-b22e-1bd52bcf0839" name="GetVisits" isLeaf="false" isStatic="true" isAbstract="false" concurrency="Sequential" isQuery="false">
            <elementDefinition Id="fe1e5117-f751-4e26-bf9c-e74459612cd5" />
            <ownedParameters>
              <operationHasOwnedParameters>
                <parameter Id="6f9f3702-dd3b-4d47-bfe1-ce5ac84a00b5" direction="Return" isUnique="false">
                  <elementDefinition Id="bde239b8-d562-4325-9f06-bd5ff2ebed40" />
                  <type_NamedElement>
                    <referencedTypeMoniker Id="b0b17692-ed70-44cf-ac5b-99a01cf9a1e6" LastKnownName="List&lt;Visit&gt;" />
                  </type_NamedElement>
                </parameter>
              </operationHasOwnedParameters>
              <operationHasOwnedParameters>
                <parameter Id="7ef3ce26-dd5f-4c8e-b9c2-e84e66ea151e" name="filterA" direction="In" isUnique="false">
                  <elementDefinition Id="82b12be7-8775-40e0-8817-73e22a1748b9" />
                  <type_NamedElement>
                    <referencedTypeMoniker Id="f7e8f999-769f-4384-8162-f7670e8b9657" LastKnownName="Visit" />
                  </type_NamedElement>
                </parameter>
              </operationHasOwnedParameters>
              <operationHasOwnedParameters>
                <parameter Id="6bc71c8d-0d5c-46d8-8cee-2624a214f9eb" name="filterB" direction="In" isUnique="false">
                  <elementDefinition Id="c912f9f2-dc45-4dec-912a-e6068a4ae890" />
                  <type_NamedElement>
                    <referencedTypeMoniker Id="f7e8f999-769f-4384-8162-f7670e8b9657" LastKnownName="Visit" />
                  </type_NamedElement>
                </parameter>
              </operationHasOwnedParameters>
              <operationHasOwnedParameters>
                <parameter Id="94183a67-7786-4132-bab1-003f4653316a" name="master" direction="In" isUnique="false">
                  <elementDefinition Id="2d05b7c5-0081-4e99-a1e6-7ba8681082c1" />
                  <type_NamedElement>
                    <referencedTypeMoniker Id="4c13560b-accc-4537-a466-aff55cd8e227" LastKnownName="Master" />
                  </type_NamedElement>
                </parameter>
              </operationHasOwnedParameters>
              <operationHasOwnedParameters>
                <parameter Id="6542c118-c983-4628-b4ef-afe653b80be7" name="sortBy" direction="In" isUnique="false">
                  <elementDefinition Id="0c4ff056-8aa8-4acd-94b0-a347ba8577b4" />
                  <type_NamedElement>
                    <referencedTypeMoniker Id="5432db89-8420-4f3f-bf54-d2b10dcc16ad" LastKnownName="string" />
                  </type_NamedElement>
                </parameter>
              </operationHasOwnedParameters>
              <operationHasOwnedParameters>
                <parameter Id="52309d28-e6d9-47f2-bc31-24be77ae5330" name="desk" direction="In" isUnique="false">
                  <elementDefinition Id="1343b019-365d-4c3f-b81f-ab25744d7565" />
                  <type_NamedElement>
                    <referencedTypeMoniker Id="6a45fed8-1689-4fa9-8e39-f876365db554" LastKnownName="bool" />
                  </type_NamedElement>
                </parameter>
              </operationHasOwnedParameters>
              <operationHasOwnedParameters>
                <parameter Id="dfb3e457-85f7-4de8-aae2-0f1c94c616d6" name="count" direction="In" isUnique="false">
                  <elementDefinition Id="c414db32-8f1e-47c0-83ce-093ecb6afe4d" />
                  <type_NamedElement>
                    <referencedTypeMoniker Id="de578a74-cb65-4d29-833c-4c0b903c29db" LastKnownName="int" />
                  </type_NamedElement>
                </parameter>
              </operationHasOwnedParameters>
              <operationHasOwnedParameters>
                <parameter Id="c9be7104-8dff-41f2-b2cf-d737b98bd51c" name="page" direction="In" isUnique="false">
                  <elementDefinition Id="6e72e405-e335-4bfe-9dfd-29d28a5876f6" />
                  <type_NamedElement>
                    <referencedTypeMoniker Id="de578a74-cb65-4d29-833c-4c0b903c29db" LastKnownName="int" />
                  </type_NamedElement>
                </parameter>
              </operationHasOwnedParameters>
            </ownedParameters>
          </operation>
          <operation Id="40b88163-6b0b-4bac-a4ce-fa1e96f44e65" name="GetById" isLeaf="false" isStatic="true" isAbstract="false" concurrency="Sequential" isQuery="false">
            <elementDefinition Id="a1cf69c5-ebf6-402e-9c05-80af3139dd92" />
            <ownedParameters>
              <operationHasOwnedParameters>
                <parameter Id="a6e67e27-374e-413d-94f4-9ed2143b0a98" name="Int" direction="In" isUnique="false">
                  <elementDefinition Id="56d4d47a-c680-4d91-8029-f053a0562108" />
                </parameter>
              </operationHasOwnedParameters>
              <operationHasOwnedParameters>
                <parameter Id="817f685e-79a7-4b83-840b-27576b6fbd1a" direction="Return" isUnique="false">
                  <elementDefinition Id="0833ae00-80d2-423e-b1a4-c4a042ffdbd9" />
                  <type_NamedElement>
                    <referencedTypeMoniker Id="f7e8f999-769f-4384-8162-f7670e8b9657" LastKnownName="Visit" />
                  </type_NamedElement>
                </parameter>
              </operationHasOwnedParameters>
            </ownedParameters>
          </operation>
        </ownedOperationsInternal>
      </class>
    </logicalClassDesignerModelHasTypes>
    <packageHasNamedElement>
      <referencedType Id="f7e8f999-769f-4384-8162-f7670e8b9657" name="Visit" isAbstract="false" isLeaf="false" cachedFullName="CompServiceClassDiagram::Visit">
        <elementDefinition Id="9993dc90-d853-4bfa-aa0b-1ad4db065e73" />
      </referencedType>
    </packageHasNamedElement>
    <packageHasNamedElement>
      <referencedType Id="d2569f2f-9059-40dc-90e8-41a6ea4616c4" name="List&lt;OrderSpareParts&gt;" isAbstract="false" isLeaf="false" cachedFullName="List&lt;OrderSpareParts&gt;">
        <elementDefinition Id="f2a59f6d-c112-44b2-97df-eca345e73998" />
      </referencedType>
    </packageHasNamedElement>
    <packageHasNamedElement>
      <referencedType Id="21f7cfc9-5064-4247-9d81-837d1a3d9114" name="DateTime" isAbstract="false" isLeaf="false" cachedFullName="DateTime">
        <elementDefinition Id="6f1e3583-6453-46eb-9e38-2685f90d378f" />
      </referencedType>
    </packageHasNamedElement>
    <logicalClassDesignerModelHasTypes>
      <class Id="615b5a0b-9df7-4ecc-9d4d-9b4ff89160e5" name="OrderLog" isAbstract="false" isLeaf="false" isActiveClass="false">
        <elementDefinition Id="6eb389a0-4e49-42c5-b0aa-cd5e601c2cc7" />
        <ownedAttributesInternal>
          <property Id="a7b563a1-6130-4bf0-a709-d0d3969f9173" name="id" isLeaf="false" isStatic="false" isReadOnly="false" isUnique="false" isDerived="false" isDerivedUnion="false" aggregation="None" isComposite="false">
            <elementDefinition Id="abec0187-e370-4d7a-aa51-484e983c06a8" />
            <type_NamedElement>
              <referencedTypeMoniker Id="bed62a32-5b87-4e40-9259-b99a5a7769a5" LastKnownName="Integer" />
            </type_NamedElement>
          </property>
          <property Id="615f83ac-5638-4198-880d-bde9a696097e" name="EventDescription" isLeaf="false" isStatic="false" isReadOnly="false" isUnique="false" isDerived="false" isDerivedUnion="false" aggregation="None" isComposite="false">
            <elementDefinition Id="be35978d-fad8-4e83-a91d-f64df9fa5951" />
            <type_NamedElement>
              <referencedTypeMoniker Id="5432db89-8420-4f3f-bf54-d2b10dcc16ad" LastKnownName="string" />
            </type_NamedElement>
          </property>
          <property Id="e3129982-acbf-4ef6-bea4-e191e41d4034" name="EventDate" isLeaf="false" isStatic="false" isReadOnly="false" isUnique="false" isDerived="false" isDerivedUnion="false" aggregation="None" isComposite="false">
            <elementDefinition Id="11b99b47-893c-4af2-ad5e-8b11766b8df6" />
            <type_NamedElement>
              <referencedTypeMoniker Id="5e95a766-896f-41c7-8951-778ddf708d7a" LastKnownName="DateTime" />
            </type_NamedElement>
          </property>
          <property Id="dda20686-ee83-4f0a-bea6-6e400898b05f" name="Order" isLeaf="false" isStatic="false" isReadOnly="false" isUnique="false" isDerived="false" isDerivedUnion="false" aggregation="None" isComposite="false">
            <elementDefinition Id="8e2ac2ce-5d9a-4e65-b80f-478e1aac9141" />
            <type_NamedElement>
              <referencedTypeMoniker Id="96762167-dba8-4e84-a426-d4426c479168" LastKnownName="Order" />
            </type_NamedElement>
          </property>
          <property Id="7a9b17a6-2db0-43eb-abdc-e159522e08b3" name="Employee" isLeaf="false" isStatic="false" isReadOnly="false" isUnique="false" isDerived="false" isDerivedUnion="false" aggregation="None" isComposite="false">
            <elementDefinition Id="fb08cc68-a2b4-4fd6-b182-d2df508651ab" />
            <type_NamedElement>
              <referencedTypeMoniker Id="448d814c-c87b-42ed-9f0f-59cb5e5b0d67" LastKnownName="Employee" />
            </type_NamedElement>
          </property>
        </ownedAttributesInternal>
        <ownedOperationsInternal>
          <operation Id="667182ae-db5d-45ca-8ba3-3bd49e468a28" name="OrderLog" isLeaf="false" isStatic="false" isAbstract="false" concurrency="Sequential" isQuery="false">
            <elementDefinition Id="934746a3-6a02-43c1-be3b-18448b0c0ca7" />
            <ownedParameters>
              <operationHasOwnedParameters>
                <parameter Id="ae1d8ec8-3f42-4f97-a18a-8140c3645c2d" direction="Return" isUnique="false">
                  <elementDefinition Id="a55fbc30-7d21-4d58-b8a6-31beb862eaaa" />
                  <type_NamedElement>
                    <referencedTypeMoniker Id="62e1c591-1fc8-4d49-889d-ba3d80faa959" LastKnownName="void" />
                  </type_NamedElement>
                </parameter>
              </operationHasOwnedParameters>
            </ownedParameters>
          </operation>
          <operation Id="70c6d526-a9dd-487f-83a6-03bdedec948b" name="AddOrderLog" isLeaf="false" isStatic="false" isAbstract="false" concurrency="Sequential" isQuery="false">
            <elementDefinition Id="90e236dd-077e-47a4-a999-6feddc02c0c2" />
            <ownedParameters>
              <operationHasOwnedParameters>
                <parameter Id="7bd37187-6cf8-4722-ba4c-49d37529db32" direction="Return" isUnique="false">
                  <elementDefinition Id="b23ea39c-e98a-4187-8cb0-5460256cc53e" />
                  <type_NamedElement>
                    <referencedTypeMoniker Id="6a45fed8-1689-4fa9-8e39-f876365db554" LastKnownName="bool" />
                  </type_NamedElement>
                </parameter>
              </operationHasOwnedParameters>
            </ownedParameters>
          </operation>
          <operation Id="a61145ac-fef4-4737-96a7-a4f5ad54a771" name="DelOrderLog" isLeaf="false" isStatic="false" isAbstract="false" concurrency="Sequential" isQuery="false">
            <elementDefinition Id="f9a498e2-4d30-4cdc-a74b-e477f420de61" />
            <ownedParameters>
              <operationHasOwnedParameters>
                <parameter Id="4897e47b-fb5d-4d9d-9e34-268c2a5beaca" direction="Return" isUnique="false">
                  <elementDefinition Id="30586f7c-7d73-43c8-9731-c4024a68949e" />
                  <type_NamedElement>
                    <referencedTypeMoniker Id="6a45fed8-1689-4fa9-8e39-f876365db554" LastKnownName="bool" />
                  </type_NamedElement>
                </parameter>
              </operationHasOwnedParameters>
            </ownedParameters>
          </operation>
        </ownedOperationsInternal>
      </class>
    </logicalClassDesignerModelHasTypes>
    <packageHasNamedElement>
      <referencedType Id="61e08e1c-740f-48fe-bf55-4101ae916fa8" name="List&lt;OrderLog&gt;" isAbstract="false" isLeaf="false" cachedFullName="List&lt;OrderLog&gt;">
        <elementDefinition Id="39a566b3-f99c-4911-9d03-c359a09496ee" />
      </referencedType>
    </packageHasNamedElement>
    <logicalClassDesignerModelHasTypes>
      <class Id="dc6a37e4-ac38-4e8a-952d-ab9fca780ff7" name="BatchSparePart" isAbstract="false" isLeaf="false" isActiveClass="false">
        <elementDefinition Id="bac14618-2f28-48e1-927a-8fb3423bec94" />
        <targetEnds>
          <association Id="9d9a345f-75d4-4cad-bb1a-90f92500bbe2" isDerived="false" sourceEndRoleName="BatchSpareParts" targetEndRoleName="SparePart" isLeaf="false" isAbstract="false">
            <classMoniker Id="eeea4536-adc9-431d-8cb2-7cad87e92193" LastKnownName="SparePart" />
            <relationshipOwnedElementsInternal>
              <associationHasOwnedEnds>
                <memberEnd Id="48e8dabb-58fc-49d9-b5db-a968f7330a51" name="BatchSpareParts" isLeaf="false" isStatic="false" isReadOnly="false" isDerived="false" isDerivedUnion="false" aggregation="Composite" isComposite="false" isNavigableOwned="false">
                  <lowerValueInternal>
                    <literalString Id="aa58925b-3946-4956-94c7-c641f3b1154c" name="Lower" value="0">
                      <elementDefinition Id="c9d674da-7c9a-44ae-972d-2dca2d90c1f8" />
                    </literalString>
                  </lowerValueInternal>
                  <upperValueInternal>
                    <literalString Id="32154d23-423a-4c9d-8493-9a0bedc9d27f" name="Upper" value="*">
                      <elementDefinition Id="8961ee60-85c3-49c2-8ad3-9a32d207e70a" />
                    </literalString>
                  </upperValueInternal>
                  <elementDefinition Id="1ba044ac-ed0d-469c-8927-669be2ae6379" />
                </memberEnd>
              </associationHasOwnedEnds>
              <associationHasOwnedEnds>
                <memberEnd Id="cf76f031-9b0e-4846-8d3a-a27fe61da8e5" name="SparePart" isLeaf="false" isStatic="false" isReadOnly="false" isDerived="false" isDerivedUnion="false" aggregation="None" isComposite="true">
                  <elementDefinition Id="0b6a2e8a-f2da-41f8-9eb0-4f99abc7b279" />
                </memberEnd>
              </associationHasOwnedEnds>
            </relationshipOwnedElementsInternal>
            <elementDefinition Id="6b5cf3ca-e018-4e17-b671-51798d1f75f5" />
          </association>
          <association Id="8cbe2542-99cd-4055-b05e-b05856d14b6f" isDerived="false" sourceEndRoleName="BatchSparePart" targetEndRoleName="Batch" isLeaf="false" isAbstract="false">
            <classMoniker Id="593cb2ed-8cab-400f-84d9-404853805b39" LastKnownName="Batch" />
            <relationshipOwnedElementsInternal>
              <associationHasOwnedEnds>
                <memberEnd Id="ec63a7b3-0878-468d-8867-1d286852c039" name="BatchSparePart" isLeaf="false" isStatic="false" isReadOnly="false" isDerived="false" isDerivedUnion="false" aggregation="Composite" isComposite="false" isNavigableOwned="false">
                  <lowerValueInternal>
                    <literalString Id="16a1fe2d-227d-41a2-8078-8c00d1e67a62" name="Lower" value="1">
                      <elementDefinition Id="9602a7d6-7b2b-4103-a184-3e58e9bdfbb0" />
                    </literalString>
                  </lowerValueInternal>
                  <upperValueInternal>
                    <literalString Id="754541c6-041a-48d6-8585-87ba8e900caa" name="Upper" value="*">
                      <elementDefinition Id="3da9cdbd-fe51-440b-abe4-dbdd870e571a" />
                    </literalString>
                  </upperValueInternal>
                  <elementDefinition Id="873d2376-9084-4285-8f52-5a408f04bda4" />
                </memberEnd>
              </associationHasOwnedEnds>
              <associationHasOwnedEnds>
                <memberEnd Id="6f8248fc-fddf-4dff-983b-48fee99ede11" name="Batch" isLeaf="false" isStatic="false" isReadOnly="false" isDerived="false" isDerivedUnion="false" aggregation="None" isComposite="true">
                  <elementDefinition Id="2b528da5-6372-461d-8d42-f3a9c21c676d" />
                </memberEnd>
              </associationHasOwnedEnds>
            </relationshipOwnedElementsInternal>
            <elementDefinition Id="c71234b6-6f5f-4846-8d18-c9c29681a3b9" />
          </association>
        </targetEnds>
        <ownedAttributesInternal>
          <property Id="0c4cf89d-98f0-4970-b7dc-83df84487a99" name="SparePart" isLeaf="false" isStatic="false" isReadOnly="false" isUnique="false" isDerived="false" isDerivedUnion="false" aggregation="None" isComposite="false">
            <elementDefinition Id="159a1aa1-c012-4a39-a10d-c858c2e8d20b" />
            <type_NamedElement>
              <referencedTypeMoniker Id="9b358894-f754-4b16-b9c4-3da490b6d799" LastKnownName="SparePart" />
            </type_NamedElement>
          </property>
          <property Id="f2d1f4db-7b14-4119-a234-a6d2dc93ec63" name="Quantity" isLeaf="false" isStatic="false" isReadOnly="false" isUnique="false" isDerived="false" isDerivedUnion="false" aggregation="None" isComposite="false">
            <elementDefinition Id="863d5e28-569b-4691-8f83-38beb33ede67" />
            <type_NamedElement>
              <referencedTypeMoniker Id="ebd2482f-9bfb-4068-96ee-3388178a6287" LastKnownName="Integer" />
            </type_NamedElement>
          </property>
          <property Id="90a95774-f512-49e8-acde-4c78b23a6acf" name="UnitPrice" isLeaf="false" isStatic="false" isReadOnly="false" isUnique="false" isDerived="false" isDerivedUnion="false" aggregation="None" isComposite="false">
            <elementDefinition Id="816a70d8-27d1-4be0-ba26-b668cdf5d4f5" />
            <type_NamedElement>
              <referencedTypeMoniker Id="883e9145-5059-46d5-bcf6-f3e93c18f6fd" LastKnownName="decimal" />
            </type_NamedElement>
          </property>
          <property Id="c35f9dee-967b-4f01-bd7a-173fdb3396d7" name="Batch" isLeaf="false" isStatic="false" isReadOnly="false" isUnique="false" isDerived="false" isDerivedUnion="false" aggregation="None" isComposite="false">
            <elementDefinition Id="28d049ef-c76e-4108-881f-7acf71698149" />
            <type_NamedElement>
              <referencedTypeMoniker Id="a983ce7e-a30b-442b-8780-478ad8636aaf" LastKnownName="Batch" />
            </type_NamedElement>
          </property>
        </ownedAttributesInternal>
        <ownedOperationsInternal>
          <operation Id="4c4200e7-d337-4149-9cf3-ad7b7825cc7a" name="BatchSpareParts" isLeaf="false" isStatic="false" isAbstract="false" concurrency="Sequential" isQuery="false">
            <elementDefinition Id="cff1d9e4-2f50-4d00-919a-52015568217d" />
            <ownedParameters>
              <operationHasOwnedParameters>
                <parameter Id="a5c6f856-3bd9-4bb8-b158-e513ba31c3fb" direction="Return" isUnique="false">
                  <elementDefinition Id="5f77f88d-c2b0-4ad3-a54c-fa194875c8e4" />
                  <type_NamedElement>
                    <referencedTypeMoniker Id="62e1c591-1fc8-4d49-889d-ba3d80faa959" LastKnownName="void" />
                  </type_NamedElement>
                </parameter>
              </operationHasOwnedParameters>
              <operationHasOwnedParameters>
                <parameter Id="0dbeaf09-c113-4e2c-a8ed-c5b060755a65" name="Batch" direction="In" isUnique="false">
                  <elementDefinition Id="9308fd8e-9784-4953-b52d-2fdbb9bdc38a" />
                </parameter>
              </operationHasOwnedParameters>
            </ownedParameters>
          </operation>
        </ownedOperationsInternal>
      </class>
    </logicalClassDesignerModelHasTypes>
    <packageHasNamedElement>
      <referencedType Id="b5531a86-0a26-4f67-88e2-aaa62ea9514d" name="Dictionary&lt;Batch, Integer&gt;" isAbstract="false" isLeaf="false" cachedFullName="Dictionary&lt;Batch, Integer&gt;">
        <elementDefinition Id="edbd46ae-c475-45e0-846d-0143a90e9b71" />
      </referencedType>
    </packageHasNamedElement>
    <packageHasNamedElement>
      <referencedType Id="633367a9-29cd-4262-a3a8-ae19491ebe33" name="List&lt;Batch&gt;" isAbstract="false" isLeaf="false" cachedFullName="List&lt;Batch&gt;">
        <elementDefinition Id="9500ff22-849f-4df1-8507-346427185d85" />
      </referencedType>
    </packageHasNamedElement>
    <packageHasNamedElement>
      <referencedType Id="35570a94-c851-4112-a001-af83a52859c2" name="String" isAbstract="false" isLeaf="false" cachedFullName="String">
        <elementDefinition Id="59259974-6d55-42c6-b7bd-763d77ac8ef9" />
      </referencedType>
    </packageHasNamedElement>
    <packageHasNamedElement>
      <referencedType Id="96e8787e-95db-4d57-93e2-e6a85b70e26b" name="decimal" isAbstract="false" isLeaf="false" cachedFullName="decimal">
        <elementDefinition Id="bb3d1d49-bf88-4270-b5ad-3f1901f7c1e5" />
      </referencedType>
    </packageHasNamedElement>
    <packageHasNamedElement>
      <referencedType Id="9ba371f3-5764-432a-b0fa-254535119fbd" name="DeteTime" isAbstract="false" isLeaf="false" cachedFullName="DeteTime">
        <elementDefinition Id="fe8e2001-abe1-4426-acf3-6a664ab22cf1" />
      </referencedType>
    </packageHasNamedElement>
    <logicalClassDesignerModelHasTypes>
      <class Id="f44e71d1-104b-44ed-86a0-4e29fb8f812c" name="OrderService" isAbstract="false" isLeaf="false" isActiveClass="false">
        <elementDefinition Id="a83edafe-3de3-45b6-856a-d388b4dc4dea" />
        <targetEnds>
          <association Id="28671a76-d2bc-4617-9508-fe81f9dd1bd2" isDerived="false" sourceEndRoleName="OrderServices" targetEndRoleName="Service" isLeaf="false" isAbstract="false">
            <classMoniker Id="60a4334c-dbe6-43a7-b0f6-19e3f89831ed" LastKnownName="Service" />
            <relationshipOwnedElementsInternal>
              <associationHasOwnedEnds>
                <memberEnd Id="c114ff0d-74a5-468a-815a-19beb045756b" name="OrderServices" isLeaf="false" isStatic="false" isReadOnly="false" isDerived="false" isDerivedUnion="false" aggregation="Composite" isComposite="false" isNavigableOwned="false">
                  <lowerValueInternal>
                    <literalString Id="e4e4758a-8859-4712-946c-fb8bddf41f5e" name="Lower" value="0">
                      <elementDefinition Id="1212f6b5-19b5-4ec8-8305-e3bbd8606d49" />
                    </literalString>
                  </lowerValueInternal>
                  <upperValueInternal>
                    <literalString Id="96562982-48b7-46ed-907f-042a83a15dc6" name="Upper" value="*">
                      <elementDefinition Id="e430d71a-987c-48f4-9052-c695b6449f13" />
                    </literalString>
                  </upperValueInternal>
                  <elementDefinition Id="c348ab56-7592-46fe-8e9b-fae9f80b0180" />
                </memberEnd>
              </associationHasOwnedEnds>
              <associationHasOwnedEnds>
                <memberEnd Id="df762860-bff8-45c9-ba18-84a81f5e6d8f" name="Service" isLeaf="false" isStatic="false" isReadOnly="false" isDerived="false" isDerivedUnion="false" aggregation="None" isComposite="true">
                  <elementDefinition Id="15dc7fb9-66c5-43c1-8d72-0acd83e74473" />
                </memberEnd>
              </associationHasOwnedEnds>
            </relationshipOwnedElementsInternal>
            <elementDefinition Id="e1815153-7a29-4198-b3fe-0f13e0efcc4d" />
          </association>
        </targetEnds>
        <ownedAttributesInternal>
          <property Id="7ed0df70-dab1-4b62-9729-8272a789b020" name="Service" isLeaf="false" isStatic="false" isReadOnly="false" isUnique="false" isDerived="false" isDerivedUnion="false" aggregation="None" isComposite="false">
            <elementDefinition Id="975f62e0-44b4-4ba8-9f46-d12727956f24" />
            <type_NamedElement>
              <referencedTypeMoniker Id="9366a8a0-2c9f-4aeb-81b2-7a52156b3689" LastKnownName="Service" />
            </type_NamedElement>
          </property>
          <property Id="373101b2-1123-452c-b8f8-70720e92940b" name="Count" isLeaf="false" isStatic="false" isReadOnly="false" isUnique="false" isDerived="false" isDerivedUnion="false" aggregation="None" isComposite="false">
            <elementDefinition Id="0204d832-1586-4055-b102-f99b37e8c486" />
            <type_NamedElement>
              <referencedTypeMoniker Id="bed62a32-5b87-4e40-9259-b99a5a7769a5" LastKnownName="Integer" />
            </type_NamedElement>
          </property>
          <property Id="6d6e0009-f843-4da8-a907-c2a603a57562" name="Sale" isLeaf="false" isStatic="false" isReadOnly="false" isUnique="false" isDerived="false" isDerivedUnion="false" aggregation="None" isComposite="false">
            <elementDefinition Id="be283163-4636-4818-86fc-c32229e7ebee" />
            <type_NamedElement>
              <referencedTypeMoniker Id="5655a02a-7ae5-4a44-9419-3de5361f9934" LastKnownName="double" />
            </type_NamedElement>
          </property>
          <property Id="402b82f1-cc1f-4209-9d03-dc1eaf36a814" name="Order" isLeaf="false" isStatic="false" isReadOnly="false" isUnique="false" isDerived="false" isDerivedUnion="false" aggregation="None" isComposite="false">
            <elementDefinition Id="b53dac3a-49b7-437a-a0c2-bf429e05302d" />
            <type_NamedElement>
              <referencedTypeMoniker Id="96762167-dba8-4e84-a426-d4426c479168" LastKnownName="Order" />
            </type_NamedElement>
          </property>
          <property Id="bc69dd98-398d-4194-ad71-0205b9d198fa" name="Done" isLeaf="false" isStatic="false" isReadOnly="false" isUnique="false" isDerived="false" isDerivedUnion="false" aggregation="None" isComposite="false">
            <elementDefinition Id="8ee213a5-96fe-42be-9111-62dbd16f8091" />
            <type_NamedElement>
              <referencedTypeMoniker Id="6a45fed8-1689-4fa9-8e39-f876365db554" LastKnownName="bool" />
            </type_NamedElement>
          </property>
          <property Id="4d36aace-57c3-4180-94e0-7aa24a188ea3" name="MasterComment" isLeaf="false" isStatic="false" isReadOnly="false" isUnique="false" isDerived="false" isDerivedUnion="false" aggregation="None" isComposite="false">
            <elementDefinition Id="34e92ba5-a8b0-49b3-9403-e64a6e129d91" />
            <type_NamedElement>
              <referencedTypeMoniker Id="faf4849f-8756-4979-b0da-605e57790912" LastKnownName="String" />
            </type_NamedElement>
          </property>
          <property Id="5e9627fc-8ab8-4316-8a37-b7c884be7343" name="Price" isLeaf="false" isStatic="false" isReadOnly="false" isUnique="false" isDerived="false" isDerivedUnion="false" aggregation="None" isComposite="false">
            <elementDefinition Id="cffe51ce-1d44-42c6-aa5f-8a57fa342ed5" />
            <type_NamedElement>
              <referencedTypeMoniker Id="d0e2218a-5be7-46cf-97a2-091e3a6a80e0" LastKnownName="decimal" />
            </type_NamedElement>
          </property>
        </ownedAttributesInternal>
        <ownedOperationsInternal>
          <operation Id="a8f8bcf3-3053-43cd-ac86-c798b625ea15" name="OrderServices" isLeaf="false" isStatic="false" isAbstract="false" concurrency="Sequential" isQuery="false">
            <elementDefinition Id="af138440-4c0b-4b1a-881b-fb654d5602b0" />
            <ownedParameters>
              <operationHasOwnedParameters>
                <parameter Id="83c28543-a853-460a-896d-9a0501435274" direction="Return" isUnique="false">
                  <elementDefinition Id="668dcb33-6e2b-4cf2-8d7c-8aaeaf160c2f" />
                  <type_NamedElement>
                    <referencedTypeMoniker Id="62e1c591-1fc8-4d49-889d-ba3d80faa959" LastKnownName="void" />
                  </type_NamedElement>
                </parameter>
              </operationHasOwnedParameters>
            </ownedParameters>
          </operation>
          <operation Id="64db401f-a3ba-4207-9b13-0dffedc28835" name="CalcFullPrice" isLeaf="false" isStatic="false" isAbstract="false" concurrency="Sequential" isQuery="false">
            <elementDefinition Id="12ccc623-1561-432b-888c-21219013f9a6" />
            <ownedParameters>
              <operationHasOwnedParameters>
                <parameter Id="5279c5d6-3435-4799-a990-585321e5fc4c" direction="Return" isUnique="false">
                  <elementDefinition Id="48e9930f-0a73-42bf-8f0c-c2bcae591fe1" />
                  <type_NamedElement>
                    <referencedTypeMoniker Id="d0e2218a-5be7-46cf-97a2-091e3a6a80e0" LastKnownName="decimal" />
                  </type_NamedElement>
                </parameter>
              </operationHasOwnedParameters>
            </ownedParameters>
          </operation>
        </ownedOperationsInternal>
      </class>
    </logicalClassDesignerModelHasTypes>
    <packageHasNamedElement>
      <referencedType Id="cef214f0-1a08-4369-af4b-81010021238c" name="List&lt;OrderServices&gt;" isAbstract="false" isLeaf="false" cachedFullName="List&lt;OrderServices&gt;">
        <elementDefinition Id="fc1a0f87-a3fa-4b33-b056-0d63220a37f6" />
      </referencedType>
    </packageHasNamedElement>
    <packageHasNamedElement>
      <referencedType Id="8171f1a1-2c1e-465d-9bbc-4fb55940dca2" name="Client" isAbstract="false" isLeaf="false" cachedFullName="CompServiceClassDiagram::Client">
        <elementDefinition Id="3cbddadd-d029-40c3-b045-8bccb04a6bc8" />
      </referencedType>
    </packageHasNamedElement>
    <packageHasNamedElement>
      <referencedType Id="883e9145-5059-46d5-bcf6-f3e93c18f6fd" name="decimal" isAbstract="false" isLeaf="false" cachedFullName="decimal">
        <elementDefinition Id="bb3d1d49-bf88-4270-b5ad-3f1901f7c1e5" />
      </referencedType>
    </packageHasNamedElement>
    <packageHasNamedElement>
      <referencedType Id="ebd2482f-9bfb-4068-96ee-3388178a6287" name="Integer" isAbstract="false" isLeaf="false" cachedFullName="Integer">
        <elementDefinition Id="220a3521-e091-4221-bae9-3ef9018e845c" />
      </referencedType>
    </packageHasNamedElement>
    <packageHasNamedElement>
      <referencedType Id="d27a172f-da7d-4650-83eb-7613dcbd12a0" name="decimal" isAbstract="false" isLeaf="false" cachedFullName="decimal">
        <elementDefinition Id="bb3d1d49-bf88-4270-b5ad-3f1901f7c1e5" />
      </referencedType>
    </packageHasNamedElement>
    <packageHasNamedElement>
      <referencedType Id="40f2070a-05f1-43ed-9aee-d973f659ad92" name="List&lt;OrderService&gt;" isAbstract="false" isLeaf="false" cachedFullName="List&lt;OrderService&gt;">
        <elementDefinition Id="f2524612-3ce9-4c06-995c-fc4329fcd653" />
      </referencedType>
    </packageHasNamedElement>
    <packageHasNamedElement>
      <referencedType Id="cf414de7-1932-44ee-a68d-62f336d10035" name="BatchSparePart" isAbstract="false" isLeaf="false" cachedFullName="CompServiceClassDiagram::BatchSparePart">
        <elementDefinition Id="bac14618-2f28-48e1-927a-8fb3423bec94" />
      </referencedType>
    </packageHasNamedElement>
    <packageHasNamedElement>
      <referencedType Id="492a3225-13c7-450a-9a5d-6a3e9d6f38b5" name="decimal" isAbstract="false" isLeaf="false" cachedFullName="decimal">
        <elementDefinition Id="bb3d1d49-bf88-4270-b5ad-3f1901f7c1e5" />
      </referencedType>
    </packageHasNamedElement>
    <packageHasNamedElement>
      <referencedType Id="f2d6aefd-92fc-4df3-9170-5a77b35a77da" name="OrderService" isAbstract="false" isLeaf="false" cachedFullName="CompServiceClassDiagram::OrderService">
        <elementDefinition Id="a83edafe-3de3-45b6-856a-d388b4dc4dea" />
      </referencedType>
    </packageHasNamedElement>
    <packageHasNamedElement>
      <referencedType Id="d56bbbbe-e00b-4780-b8ab-6e56eef1a8fc" name="Permission" isAbstract="false" isLeaf="false" cachedFullName="CompServiceClassDiagram::Permission">
        <elementDefinition Id="0b93d8d6-c2f6-4ae8-b2f0-289a8424fe88" />
      </referencedType>
    </packageHasNamedElement>
    <logicalClassDesignerModelHasTypes>
      <enumeration Id="1e4c5d5c-23f7-4f86-a109-9163f1744fd8" name="RoleType" isAbstract="false" isLeaf="false">
        <elementDefinition Id="52b0dd5e-950e-4413-96fd-4804b4959a2a" />
        <suppliersInternal>
          <dependency Id="9533e82b-bfed-4829-aea7-d04760f602fe">
            <classMoniker Id="49e29943-c54c-45f2-9af3-97e7397fbc62" LastKnownName="Role" />
            <elementDefinition Id="939612a7-4712-422e-801e-b395b17ab47f" />
          </dependency>
        </suppliersInternal>
        <ownedLiterals>
          <enumerationLiteral Id="c6776466-3920-4094-b36d-c9eb49a85483" name="Master">
            <elementDefinition Id="83572e90-f3c0-466e-827a-a0630214dd96" />
          </enumerationLiteral>
          <enumerationLiteral Id="1f4002cf-d06c-4904-ac91-7a560eef403f" name="Manager">
            <elementDefinition Id="5be76005-cb39-4b03-b89b-247fab7bbec7" />
          </enumerationLiteral>
          <enumerationLiteral Id="a254db51-f039-48fe-a20c-a8de0e46770c" name="Anyone">
            <elementDefinition Id="a7ed2b11-16f6-4f66-8b5a-34b4198a466e" />
          </enumerationLiteral>
        </ownedLiterals>
      </enumeration>
    </logicalClassDesignerModelHasTypes>
    <packageHasNamedElement>
      <referencedType Id="692b2aee-bd60-4b53-a628-86edf58087d0" name="Datetime" isAbstract="false" isLeaf="false" cachedFullName="Datetime">
        <elementDefinition Id="42896087-0971-43c1-982b-06af3ffb8565" />
      </referencedType>
    </packageHasNamedElement>
    <packageHasNamedElement>
      <referencedType Id="f8fa7e64-5d47-4185-9119-20c7b0ef1db1" name="DateTime" isAbstract="false" isLeaf="false" cachedFullName="DateTime">
        <elementDefinition Id="6f1e3583-6453-46eb-9e38-2685f90d378f" />
      </referencedType>
    </packageHasNamedElement>
    <packageHasNamedElement>
      <referencedType Id="f6b29dd0-39a0-4152-918d-8671f63fda18" name="OrderSparePart" isAbstract="false" isLeaf="false" cachedFullName="CompServiceClassDiagram::OrderSparePart">
        <elementDefinition Id="e1defe16-18b3-498d-b93d-a4659b854e0f" />
      </referencedType>
    </packageHasNamedElement>
    <packageHasNamedElement>
      <referencedType Id="a3d344e5-b1ee-4651-a6ac-7c3164dea949" name="OrderLog" isAbstract="false" isLeaf="false" cachedFullName="CompServiceClassDiagram::OrderLog">
        <elementDefinition Id="6eb389a0-4e49-42c5-b0aa-cd5e601c2cc7" />
      </referencedType>
    </packageHasNamedElement>
    <packageHasNamedElement>
      <referencedType Id="643c642d-bc85-4c20-b8ce-cbf116cd79cd" name="SparePart" isAbstract="false" isLeaf="false" cachedFullName="CompServiceClassDiagram::SparePart">
        <elementDefinition Id="3113cd22-0eb7-43e8-bafb-033a4008083a" />
      </referencedType>
    </packageHasNamedElement>
    <logicalClassDesignerModelHasTypes>
      <enumeration Id="d75b1f79-d8f4-4c91-8292-10f283960448" name="BatchStatus" isAbstract="false" isLeaf="false">
        <elementDefinition Id="14186085-41a4-40c7-93b6-549a47c7d21d" />
        <suppliersInternal>
          <dependency Id="517546d0-0600-4008-b459-d31d38246884">
            <classMoniker Id="593cb2ed-8cab-400f-84d9-404853805b39" LastKnownName="Batch" />
            <elementDefinition Id="b9c60055-2573-40b9-9110-822d20958af6" />
          </dependency>
        </suppliersInternal>
        <ownedLiterals>
          <enumerationLiteral Id="43baece4-8f77-4801-942e-a113d87ad79d" name="Created">
            <elementDefinition Id="3a6d56fa-6ec9-45c8-8f36-62669142919e" />
          </enumerationLiteral>
          <enumerationLiteral Id="631d302c-1dde-4b89-955f-cbf403827e91" name="Delivered">
            <elementDefinition Id="bb2ed705-71b7-4b4d-befd-039eeb2a0346" />
          </enumerationLiteral>
          <enumerationLiteral Id="d5dacf74-204c-46b0-9f50-4d9aa0610dc3" name="Confirmed">
            <elementDefinition Id="ff3c8573-85b9-4da9-8fc1-e8c6cad397e1" />
          </enumerationLiteral>
        </ownedLiterals>
      </enumeration>
    </logicalClassDesignerModelHasTypes>
    <packageHasNamedElement>
      <referencedType Id="9b358894-f754-4b16-b9c4-3da490b6d799" name="SparePart" isAbstract="false" isLeaf="false" cachedFullName="CompServiceClassDiagram::SparePart">
        <elementDefinition Id="3113cd22-0eb7-43e8-bafb-033a4008083a" />
      </referencedType>
    </packageHasNamedElement>
  </packagedElements>
  <package Id="daa639ff-2fb2-4b9a-b23a-20b1161631fe" name="CompServiceClassDiagram">
    <elementDefinition Id="6466aa03-05f8-4bd3-ae9e-75adbc5d922c" />
    <profileInstances>
      <packageHasProfileInstances Id="83b3aff3-228d-4b6c-8c62-54ddfcfd10f4">
        <profileInstance Id="c7f5566f-5a1c-4729-b7de-7e8464c4a226" name="StandardProfileL2">
          <elementDefinition Id="e34d544e-0fea-4ed6-ac5e-1b74119ac791" />
        </profileInstance>
        <elementDefinition Id="0caec977-1f8c-4ba3-a7db-8cc9ad9cc73b" />
      </packageHasProfileInstances>
      <packageHasProfileInstances Id="ca107c2f-a4a9-4c6b-90df-8dba5dde2e8f">
        <profileInstance Id="e0f1d68c-d4a8-40f5-9387-e37023ac2726" name="StandardProfileL3">
          <elementDefinition Id="532ea607-fb19-44b8-8502-3351b05452be" />
        </profileInstance>
        <elementDefinition Id="29349502-908c-4fda-9054-c48619c59ed0" />
      </packageHasProfileInstances>
    </profileInstances>
  </package>
</logicalClassDesignerModel>