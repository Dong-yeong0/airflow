
 .. Licensed to the Apache Software Foundation (ASF) under one
    or more contributor license agreements.  See the NOTICE file
    distributed with this work for additional information
    regarding copyright ownership.  The ASF licenses this file
    to you under the Apache License, Version 2.0 (the
    "License"); you may not use this file except in compliance
    with the License.  You may obtain a copy of the License at

 ..   http://www.apache.org/licenses/LICENSE-2.0

 .. Unless required by applicable law or agreed to in writing,
    software distributed under the License is distributed on an
    "AS IS" BASIS, WITHOUT WARRANTIES OR CONDITIONS OF ANY
    KIND, either express or implied.  See the License for the
    specific language governing permissions and limitations
    under the License.

 .. NOTE! THIS FILE IS AUTOMATICALLY GENERATED AND WILL BE OVERWRITTEN!

 .. IF YOU WANT TO MODIFY THIS FILE, YOU SHOULD MODIFY THE TEMPLATE
    `PROVIDER_COMMITS_TEMPLATE.rst.jinja2` IN the `dev/breeze/src/airflow_breeze/templates` DIRECTORY

 .. THE REMAINDER OF THE FILE IS AUTOMATICALLY GENERATED. IT WILL BE OVERWRITTEN!

Package apache-airflow-providers-apprise
------------------------------------------------------

`Apprise <https://github.com/caronc/apprise>`__


This is detailed commit list of changes for versions provider package: ``apprise``.
For high-level changelog, see :doc:`package information including changelog <index>`.



2.0.1
.....

Latest change: 2025-03-05

==================================================================================================  ===========  =====================================================================
Commit                                                                                              Committed    Subject
==================================================================================================  ===========  =====================================================================
`e4002c3305 <https://github.com/apache/airflow/commit/e4002c3305a757f5926f96c996e701e8f998a042>`__  2025-03-05   ``Move tests_common package to devel-common project (#47281)``
`1addb55154 <https://github.com/apache/airflow/commit/1addb55154fbef31bfa021537cfbd4395696381c>`__  2025-02-28   ``Improve documentation for updating provider dependencies (#47203)``
`c6c4f95ed9 <https://github.com/apache/airflow/commit/c6c4f95ed9e3220133815b9126c135e805637022>`__  2025-02-25   ``Add legacy namespace packages to airflow.providers (#47064)``
`dbf8bb4092 <https://github.com/apache/airflow/commit/dbf8bb409223687c7d2ad10649a92d02c24bb3b4>`__  2025-02-24   ``Remove extra whitespace in provider readme template (#46975)``
`b28c336e8b <https://github.com/apache/airflow/commit/b28c336e8b7aa1d69c0f9520b182b1b661377337>`__  2025-02-21   ``Upgrade flit to 3.11.0 (#46938)``
`5d87bddf0a <https://github.com/apache/airflow/commit/5d87bddf0aa5f485f3684c909fb95f461e5a2ab6>`__  2025-02-21   ``Prepare docs for Feb 1st wave of providers (#46893)``
`4d5846f58f <https://github.com/apache/airflow/commit/4d5846f58fe0de9b43358c0be75dd72e968dacc4>`__  2025-02-16   ``Move provider_tests to unit folder in provider tests (#46800)``
`e027457a24 <https://github.com/apache/airflow/commit/e027457a24d0c6235bfed9c2a8399f75342e82f1>`__  2025-02-15   ``Removed the unused provider's distribution (#46608)``
`e6ea6709bb <https://github.com/apache/airflow/commit/e6ea6709bbd8ba7c024c4f75136a0af0cf9987b0>`__  2025-02-04   ``Moving EmptyOperator to standard provider (#46231)``
`09d280a0ed <https://github.com/apache/airflow/commit/09d280a0edb094102ae014c290c11b782b2b31e6>`__  2025-01-30   ``Move Apprise provider to new structure (#46161)``
==================================================================================================  ===========  =====================================================================

2.0.0
.....

Latest change: 2024-12-20

==================================================================================================  ===========  ====================================================================
Commit                                                                                              Committed    Subject
==================================================================================================  ===========  ====================================================================
`2723508345 <https://github.com/apache/airflow/commit/2723508345d5cf074aeb673955ce72996785f2bc>`__  2024-12-20   ``Prepare docs for Nov 1st wave of providers Dec 2024 (#45042)``
`4b38bed76c <https://github.com/apache/airflow/commit/4b38bed76c1ea5fe84a6bc678ce87e20d563adc0>`__  2024-12-16   ``Bump min version of Providers to 2.9 (#44956)``
`7f42a77ca6 <https://github.com/apache/airflow/commit/7f42a77ca6096c147983f8a8bae7db362821e6fb>`__  2024-12-07   ``Remove Provider Deprecations in Apprise (#44764)``
`1275fec92f <https://github.com/apache/airflow/commit/1275fec92fd7cd7135b100d66d41bdcb79ade29d>`__  2024-11-24   ``Use Python 3.9 as target version for Ruff & Black rules (#44298)``
==================================================================================================  ===========  ====================================================================

1.4.1
.....

Latest change: 2024-11-14

==================================================================================================  ===========  ========================================================================================
Commit                                                                                              Committed    Subject
==================================================================================================  ===========  ========================================================================================
`a53d9f6d25 <https://github.com/apache/airflow/commit/a53d9f6d257f193ea5026ba4cd007d5ddeab968f>`__  2024-11-14   ``Prepare docs for Nov 1st wave of providers (#44011)``
`857ca4c06c <https://github.com/apache/airflow/commit/857ca4c06c9008593674cabdd28d3c30e3e7f97b>`__  2024-10-09   ``Split providers out of the main "airflow/" tree into a UV workspace project (#42505)``
`a5ffbbda17 <https://github.com/apache/airflow/commit/a5ffbbda17450a5c99037b292844087119b5676a>`__  2024-10-09   ``Standard provider bash operator (#42252)``
`e8a5996891 <https://github.com/apache/airflow/commit/e8a59968918e84a6221cd72cb3a8c6ddb563840c>`__  2024-08-26   ``Unify DAG schedule args and change default to None (#41453)``
==================================================================================================  ===========  ========================================================================================

1.4.0
.....

Latest change: 2024-08-19

==================================================================================================  ===========  =======================================================================
Commit                                                                                              Committed    Subject
==================================================================================================  ===========  =======================================================================
`75fb7acbac <https://github.com/apache/airflow/commit/75fb7acbaca09a040067f0a5a37637ff44eb9e14>`__  2024-08-19   ``Prepare docs for Aug 2nd wave of providers (#41559)``
`fcbff15bda <https://github.com/apache/airflow/commit/fcbff15bda151f70db0ca13fdde015bace5527c4>`__  2024-08-12   ``Bump minimum Airflow version in providers to Airflow 2.8.0 (#41396)``
==================================================================================================  ===========  =======================================================================

1.3.2
.....

Latest change: 2024-08-03

==================================================================================================  ===========  =======================================================================
Commit                                                                                              Committed    Subject
==================================================================================================  ===========  =======================================================================
`d23881c648 <https://github.com/apache/airflow/commit/d23881c6489916113921dcedf85077441b44aaf3>`__  2024-08-03   ``Prepare docs for Aug 1st wave of providers (#41230)``
`67f117060e <https://github.com/apache/airflow/commit/67f117060e3a62556b92f8fbc8e2b7837d0c231c>`__  2024-08-01   ``Fix default behaviour for init function in AppriseNotifier (#41054)``
==================================================================================================  ===========  =======================================================================

1.3.1
.....

Latest change: 2024-05-26

==================================================================================================  ===========  ===================================================
Commit                                                                                              Committed    Subject
==================================================================================================  ===========  ===================================================
`34500f3a2f <https://github.com/apache/airflow/commit/34500f3a2fa4652272bc831e3c18fd2a6a2da5ef>`__  2024-05-26   ``Prepare docs 3rd wave May 2024 (#39738)``
`79042cff41 <https://github.com/apache/airflow/commit/79042cff416296c8bdbd64f2e0a5f4d46c93e882>`__  2024-05-13   ``Fix Apprise Mypy checks added in 1.8.0 (#39580)``
`2b1a2f8d56 <https://github.com/apache/airflow/commit/2b1a2f8d561e569df194c4ee0d3a18930738886e>`__  2024-05-11   ``Reapply templates for all providers (#39554)``
`2c05187b07 <https://github.com/apache/airflow/commit/2c05187b07baf7c41a32b18fabdbb3833acc08eb>`__  2024-05-10   ``Faster 'airflow_version' imports (#39552)``
`73918925ed <https://github.com/apache/airflow/commit/73918925edaf1c94790a6ad8bec01dec60accfa1>`__  2024-05-08   ``Simplify 'airflow_version' imports (#39497)``
==================================================================================================  ===========  ===================================================

1.3.0
.....

Latest change: 2024-05-01

==================================================================================================  ===========  =======================================================================
Commit                                                                                              Committed    Subject
==================================================================================================  ===========  =======================================================================
`fe4605a10e <https://github.com/apache/airflow/commit/fe4605a10e26f1b8a180979ba5765d1cb7fb0111>`__  2024-05-01   ``Prepare docs 1st wave May 2024 (#39328)``
`ead9b00f7c <https://github.com/apache/airflow/commit/ead9b00f7cd5acecf9d575c459bb62633088436a>`__  2024-04-25   ``Bump minimum Airflow version in providers to Airflow 2.7.0 (#39240)``
`5fa80b6aea <https://github.com/apache/airflow/commit/5fa80b6aea60f93cdada66f160e2b54f723865ca>`__  2024-04-10   ``Prepare docs 1st wave (RC1) April 2024 (#38863)``
`83316b8158 <https://github.com/apache/airflow/commit/83316b81584c9e516a8142778fc509f19d95cc3e>`__  2024-03-04   ``Prepare docs 1st wave (RC1) March 2024 (#37876)``
`5a0be392e6 <https://github.com/apache/airflow/commit/5a0be392e66f8e5426ba3478621115e92fcf245b>`__  2024-02-16   ``Add comment about versions updated by release manager (#37488)``
==================================================================================================  ===========  =======================================================================

1.2.2
.....

Latest change: 2024-02-12

==================================================================================================  ===========  ====================================================================================================================
Commit                                                                                              Committed    Subject
==================================================================================================  ===========  ====================================================================================================================
`bfb054e9e8 <https://github.com/apache/airflow/commit/bfb054e9e867b8b9a6a449e43bfba97f645e025e>`__  2024-02-12   ``Prepare docs 1st wave of Providers February 2024 (#37326)``
`f61ffe58d3 <https://github.com/apache/airflow/commit/f61ffe58d3cd0bcb51f6f9036a3acbfa4443d977>`__  2024-02-11   ``Remove extra package headers in provider indexes (#37324)``
`250f29fc8a <https://github.com/apache/airflow/commit/250f29fc8a600678ffa9cb8382f32cea3b0d5796>`__  2024-02-08   ``Simplified configuration parsing in Apprise Connection (#37202)``
`cead3da4a6 <https://github.com/apache/airflow/commit/cead3da4a6f483fa626b81efd27a24dcb5a36ab0>`__  2024-01-26   ``Add docs for RC2 wave of providers for 2nd round of Jan 2024 (#37019)``
`0b680c9492 <https://github.com/apache/airflow/commit/0b680c94922e3f7ca1f3ada8328e315bbae37dc8>`__  2024-01-26   ``Revert "Provide the logger_name param in providers hooks in order to override the logger name (#36675)" (#37015)``
`2b4da0101f <https://github.com/apache/airflow/commit/2b4da0101f0314989d148c3c8a02c87e87048974>`__  2024-01-22   ``Prepare docs 2nd wave of Providers January 2024 (#36945)``
`6bd450da1e <https://github.com/apache/airflow/commit/6bd450da1eb6cacc2ccfd4544d520ae059b75c3b>`__  2024-01-10   ``Provide the logger_name param in providers hooks in order to override the logger name (#36675)``
`19ebcac239 <https://github.com/apache/airflow/commit/19ebcac2395ef9a6b6ded3a2faa29dc960c1e635>`__  2024-01-07   ``Prepare docs 1st wave of Providers January 2024 (#36640)``
`6937ae7647 <https://github.com/apache/airflow/commit/6937ae76476b3bc869ef912d000bcc94ad642db1>`__  2023-12-30   ``Speed up autocompletion of Breeze by simplifying provider state (#36499)``
==================================================================================================  ===========  ====================================================================================================================

1.2.1
.....

Latest change: 2023-12-23

==================================================================================================  ===========  ==================================================================================
Commit                                                                                              Committed    Subject
==================================================================================================  ===========  ==================================================================================
`b15d5578da <https://github.com/apache/airflow/commit/b15d5578dac73c4c6a3ca94d90ab0dc9e9e74c9c>`__  2023-12-23   ``Re-apply updated version numbers to 2nd wave of providers in December (#36380)``
`f5883d6e7b <https://github.com/apache/airflow/commit/f5883d6e7be83f1ab9468e67164b7ac381fdb49f>`__  2023-12-23   ``Prepare 2nd wave of providers in December (#36373)``
`cd476acd8f <https://github.com/apache/airflow/commit/cd476acd8f1684f613c20dddaa9e988bcfb3ac1c>`__  2023-12-11   ``Follow BaseHook connection fields method signature in child classes (#36086)``
==================================================================================================  ===========  ==================================================================================

1.2.0
.....

Latest change: 2023-12-08

==================================================================================================  ===========  =======================================================================
Commit                                                                                              Committed    Subject
==================================================================================================  ===========  =======================================================================
`999b70178a <https://github.com/apache/airflow/commit/999b70178a1f5d891fd2c88af4831a4ba4c2cbc9>`__  2023-12-08   ``Prepare docs 1st wave of Providers December 2023 (#36112)``
`d0918d77ee <https://github.com/apache/airflow/commit/d0918d77ee05ab08c83af6956e38584a48574590>`__  2023-12-07   ``Bump minimum Airflow version in providers to Airflow 2.6.0 (#36017)``
`0b23d5601c <https://github.com/apache/airflow/commit/0b23d5601c6f833392b0ea816e651dcb13a14685>`__  2023-11-24   ``Prepare docs 2nd wave of Providers November 2023 (#35836)``
`99534e47f3 <https://github.com/apache/airflow/commit/99534e47f330ce0efb96402629dda5b2a4f16e8f>`__  2023-11-19   ``Use reproducible builds for provider packages (#35693)``
`99df205f42 <https://github.com/apache/airflow/commit/99df205f42a754aa67f80b5983e1d228ff23267f>`__  2023-11-16   ``Fix and reapply templates for provider documentation (#35686)``
`1b059c57d6 <https://github.com/apache/airflow/commit/1b059c57d6d57d198463e5388138bee8a08591b1>`__  2023-11-08   ``Prepare docs 1st wave of Providers November 2023 (#35537)``
`706878ec35 <https://github.com/apache/airflow/commit/706878ec354cf867440c367a95c85753c19e54de>`__  2023-11-04   ``Remove empty lines in generated changelog (#35436)``
`052e26ad47 <https://github.com/apache/airflow/commit/052e26ad473a9d50f0b96456ed094f2087ee4434>`__  2023-11-04   ``Change security.rst to use includes in providers (#35435)``
`d1c58d86de <https://github.com/apache/airflow/commit/d1c58d86de1267d9268a1efe0a0c102633c051a1>`__  2023-10-28   ``Prepare docs 3rd wave of Providers October 2023 - FIX (#35233)``
`3592ff4046 <https://github.com/apache/airflow/commit/3592ff40465032fa041600be740ee6bc25e7c242>`__  2023-10-28   ``Prepare docs 3rd wave of Providers October 2023 (#35187)``
`dd7ba3cae1 <https://github.com/apache/airflow/commit/dd7ba3cae139cb10d71c5ebc25fc496c67ee784e>`__  2023-10-19   ``Pre-upgrade 'ruff==0.0.292' changes in providers (#35053)``
==================================================================================================  ===========  =======================================================================

1.1.0
.....

Latest change: 2023-10-13

==================================================================================================  ===========  ===============================================================
Commit                                                                                              Committed    Subject
==================================================================================================  ===========  ===============================================================
`e9987d5059 <https://github.com/apache/airflow/commit/e9987d50598f70d84cbb2a5d964e21020e81c080>`__  2023-10-13   ``Prepare docs 1st wave of Providers in October 2023 (#34916)``
`0c8e30e43b <https://github.com/apache/airflow/commit/0c8e30e43b70e9d033e1686b327eb00aab82479c>`__  2023-10-05   ``Bump min airflow version of providers (#34728)``
==================================================================================================  ===========  ===============================================================

1.0.2
.....

Latest change: 2023-09-08

==================================================================================================  ===========  ===================================================================================================
Commit                                                                                              Committed    Subject
==================================================================================================  ===========  ===================================================================================================
`21990ed894 <https://github.com/apache/airflow/commit/21990ed8943ee4dc6e060ee2f11648490c714a3b>`__  2023-09-08   ``Prepare docs for 09 2023 - 1st wave of Providers (#34201)``
`4610df1ecf <https://github.com/apache/airflow/commit/4610df1ecf9f2a91621b0df80767b2ce2164113e>`__  2023-09-01   ``Reformat Apprise and Amazon Chime connections docs (#33971)``
`6c943ca5d2 <https://github.com/apache/airflow/commit/6c943ca5d2a3fc38325cbd76e229705c697971ec>`__  2023-08-28   ``Resolve D301 in Apprise Provider (#33852)``
`9d8c77e447 <https://github.com/apache/airflow/commit/9d8c77e447f5515b9a6aa85fa72511a86a128c28>`__  2023-08-27   ``Improve modules import in Airflow providers by some of them into a type-checking block (#33754)``
`c077d19060 <https://github.com/apache/airflow/commit/c077d190609f931387c1fcd7b8cc34f12e2372b9>`__  2023-08-26   ``Prepare docs for Aug 2023 3rd wave of Providers (#33730)``
`c645d8e40c <https://github.com/apache/airflow/commit/c645d8e40c167ea1f6c332cdc3ea0ca5a9363205>`__  2023-08-12   ``D401 Support - Providers: Airbyte to Atlassian (Inclusive) (#33354)``
==================================================================================================  ===========  ===================================================================================================

1.0.1
.....

Latest change: 2023-07-29

==================================================================================================  ===========  ===========================================================================
Commit                                                                                              Committed    Subject
==================================================================================================  ===========  ===========================================================================
`d06b7af69a <https://github.com/apache/airflow/commit/d06b7af69a65c50321ba2a9904551f3b8affc7f1>`__  2023-07-29   ``Prepare docs for July 2023 3rd wave of Providers (#32875)``
`9194144dab <https://github.com/apache/airflow/commit/9194144dab01d1898877215379e1c019fe6f10cd>`__  2023-07-27   ``Replace Ruff setting known-third-party with namespace-packages (#32873)``
`73b90c48b1 <https://github.com/apache/airflow/commit/73b90c48b1933b49086d34176527947bd727ec85>`__  2023-07-21   ``Allow configuration to be contributed by providers (#32604)``
==================================================================================================  ===========  ===========================================================================

1.0.0
.....

Latest change: 2023-07-06

==================================================================================================  ===========  ===================================================================
Commit                                                                                              Committed    Subject
==================================================================================================  ===========  ===================================================================
`225e3041d2 <https://github.com/apache/airflow/commit/225e3041d269698d0456e09586924c1898d09434>`__  2023-07-06   ``Prepare docs for July 2023 wave of Providers (RC2) (#32381)``
`3878fe6fab <https://github.com/apache/airflow/commit/3878fe6fab3ccc1461932b456c48996f2763139f>`__  2023-07-05   ``Remove spurious headers for provider changelogs (#32373)``
`cb4927a018 <https://github.com/apache/airflow/commit/cb4927a01887e2413c45d8d9cb63e74aa994ee74>`__  2023-07-05   ``Prepare docs for July 2023 wave of Providers (#32298)``
`8c37b74a20 <https://github.com/apache/airflow/commit/8c37b74a208a808d905c1b86d081d69d7a1aa900>`__  2023-06-28   ``D205 Support - Providers: Apache to Common (inclusive) (#32226)``
`09d4718d3a <https://github.com/apache/airflow/commit/09d4718d3a46aecf3355d14d3d23022002f4a818>`__  2023-06-27   ``Improve provider documentation and README structure (#32125)``
`f4c4b77486 <https://github.com/apache/airflow/commit/f4c4b7748655cd11d2c297de38563b2e6b840221>`__  2023-06-21   ``Add Apprise Provider   (#31533)``
==================================================================================================  ===========  ===================================================================
