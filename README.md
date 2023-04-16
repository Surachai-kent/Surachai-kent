- 👋 Hi, I’m @Surachai-kent
- 👀 I’m interested in ...
- 🌱 I’m currently learning ...
- 💞️ I’m looking to collaborate on ...
- 📫 How to reach me ...

<!---
Surachai-kent/Surachai-kent is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
Title: Third-Party Licensing Policy - The Apache Software Foundation
Atom: http://mail-archives.apache.org/mod_mbox/www-legal-discuss/?format=atom
      "ASF legal-discuss Mailing List"
Notice:    Licensed to the Apache Software Foundation (ASF) under one
           or more contributor license agreements.  See the NOTICE file
           distributed with this work for additional information
           regarding copyright ownership.  The ASF licenses this file
           to you under the Apache License, Version 2.0 (the
           "License"); you may not use this file except in compliance
           with the License.  You may obtain a copy of the License at
           .
             http://www.apache.org/licenses/LICENSE-2.0
           .
           Unless required by applicable law or agreed to in writing,
           software distributed under the License is distributed on an
           "AS IS" BASIS, WITHOUT WARRANTIES OR CONDITIONS OF ANY
           KIND, either express or implied.  See the License for the
           specific language governing permissions and limitations
           under the License.

# Third-Party Licensing Policy #

## Status ## {#status}
<div class="section-content">

### Version: 0.54 ### {#version}

<div class="section-content">
</div>

###<h3>Effective Date: N/A (proposed) ### {#effectivedate}

<div class="section-content">
<p style="font-size: x-large"><i>This document represented a <u>proposed</u> ASF policy that was very helpful in guiding the foundation for a number of years.
<br>

Please refer to the <a href="resolved.html">official version</a> that was derived from this 
draft and associated feedback.</i></p>
</div>

<p style="font-size: x-large"><b>THE REST OF THIS DOCUMENT IS OF HISTORIC INTEREST <u>ONLY</u></b>
<br>

</p>


   <a name="audience"><h3>Intended Audience</h3></a>

<div class="section-content">
<p>This policy is primarily intended for Apache committers and PMC members.
While it can help users understand what governs the inclusion of third-party works
within Apache products, it does not place any requirements on users.  The LICENSE file within each product
includes and/or references the only applicable licensing terms.  
</p>
</div>
</div>
## Overview
           
<div class="section-content">
<p>
This document defines the Apache Software Foundation's third-party licensing policy, specifying 
<a href="#category-a">which licenses are acceptable for use</a> with an Apache product, 
<a href="#category-x">which licenses are not</a>, and how to handle each case.  The policy 
applies to all works developed outside the ASF that are being considered for use with or inclusion within an Apache product.
</p>
<p>
This policy is divided into the following sections:
<ul>
<li><a href="#principles">Guiding Principles</a></li>
<li><a href="#criteriaandcategories">Software License Criteria and Categories</a></li>
<li><a href="#labeling">License Labeling Requirement</a></li>
<li><a href="#options">Options for Prohibited Works</a></li>
<li><a href="#transition">Transition and Exceptions</a></li>
<li><a href="#appendix">Appendix: Definitions and Contact Info</a></li>
</ul>

A forthcoming policy will address the detailed procedures for accepting and 
distributing contributions, including those considered <a href="#define-thirdpartywork">third-party works</a>.
</p>
</div>
           
   <a name="principles"><h2>Guiding Principles</h2></a>

<div class="section-content">
<p>
The policies outlined in this document are designed to meet the following guiding principles:
<ol>
<li><a name="principle1"> </a>The ASF must be able to distribute works created within an Apache Project solely under the Apache License.</li>
<li><a name="principle2"> </a>The licensing connotation of the Apache brand must be maintained by ensuring all software in an  
Apache product, including third-party works, is licensed under the <a href="http://apache.org/licenses/LICENSE-2.0">Apache License</a> 
or <a href="#criteria">similar terms</a> and that steps are taken to minimize any practical impact on the user due to any 
difference in terms.</li>
<li><a name="principle3"> </a>Committers must be provided with a clear policy that identifies when a third-party work can be 
included within an Apache product and that addresses the practical issue of releasing products that depend on other software.</li> 
<li><a name="principle4"> </a>Users of Apache products must be provided with all licensing terms applicable to any part of the product 
and must be given prominent notice when any of those terms include restrictions significantly different from the Apache License.</li>
</ol>
</p>
</div>
           
   <a name="criteriaandcategories"><h2>Software License Criteria and Categories</h2></a>

<div class="section-content">

   <a name="criteria"><h3>Software License Criteria</h3></a>

<div class="section-content">
<p>The following criteria serve to fulfill the first two <a href="#principles">guiding principles</a> of this policy, 
as described above.
<ol>
<li><a name="criterion1"> </a>The license must meet the <a href="http://opensource.org/docs/definition.php">Open Source Definition</a>.</li>
<li><a name="criterion2"> </a>The license must not place restrictions on the distribution of independent works that simply use or 
contain the covered work.</li>
<li><a name="criterion3"> </a>The license must not place restrictions on the distribution of <a href="#define-largerwork">larger works</a>, 
other than to require that the covered component still complies with the conditions of its license.</li>
</ol>
</p>
<p><a name="criterion-reciprocity"> </a>
In addition to these requirements, if the license requires any degree of <a href="#define-reciprocal">reciprocity</a>, 
the ASF distribution must be prominently labeled to indicate the inclusion of software under <a href="#define-reciprocal">reciprocal</a> terms.
</p>
</div>

   <a name="categories"><h3>License Categories</h3></a>

<div class="section-content">
<p>
The lists below declare which licenses are authorized and which licenses are 
excluded from applying to any part of a product distributed by an ASF PMC.  Categorized lists of licenses
are used in this policy to address the <a href="#principle3">third guiding principle of this policy</a>.</p>
<p>  
<i>Even optional works must adhere to this policy if they are included as 
part of the Apache product.</i>  See <a href="#options">Options for Prohibited 
Works</a> for more details on what can be done with an <a href="#category-x">excluded license</a>, 
including issues related to <a href="#options-optional">optional add-ons</a> and <a href="#options-systemrequirements">system requirements</a>.
</p>
<p>NOTE: Licenses not appearing on these lists must be explicitly approved by the ASF Legal Affairs 
officer prior to distribution.  License approval requests may be sent to the <a href="http://www.apache.org/foundation/mailinglists.html#foundation-legal">legal-discuss mailing list</a>.  
</p>
<p>NOTE: Some licenses listed below do not include version numbers, in which case the 
specific version referred to is the one <a href="http://opensource.org/licenses/">posted on the OSI site</a>.
</p>

   <a name="category-a"><h4> Category A: Authorized Licenses</h4> </a> 

<div class="section-content">
<p><a href="#define-thirdpartywork">Third-party works</a>, in both <a href="#define-source">source</a> and <a href="#define-binary">binary</a> form, 
may be included within Apache products when made available under the following licenses:
</p>
<ul>
<li><a href="http://apache.org/licenses/LICENSE-2.0">Apache License 2.0</a></li>
<li><a href="http://apache.org/licenses/LICENSE-1.1">ASL 1.1</a></li>
<li><a href="http://opensource.org/licenses/bsd-license.php">BSD</a></li>
<li><a href="http://opensource.org/licenses/mit-license.php">MIT/X11</a></li>
<li><a href="http://opensource.org/licenses/UoI-NCSA.php">NCSA</a></li>
<li><a href="http://opensource.org/licenses/W3C.php">W3C Software license</a></li>
<li><a href="http://opensource.org/licenses/xnet.php">X.Net</a></li>
<li><a href="http://opensource.org/licenses/zlib-license.php">zlib/libpng</a></li>
</ul>
</div>
 
   <a name="category-b"><h4>Category B: Reciprocal Licenses</h4></a> 

<div class="section-content">
<p>
Each license in this category requires some degree of <a href="#define-reciprocal">reciprocity</a>; therefore, additional action must be taken in order
to <i>minimize the chance</i> that a user of an Apache product
will create a derivative work of a reciprocally-licensed portion of an Apache product without being aware of the applicable 
requirements.</p>
<p>
The first action that must be taken is that software under the following licenses may only be included within an Apache product if the inclusion is <a href="#labeling-reciprocity">appropriately labeled</a>:

<ul>
<li><a href="http://opensource.org/licenses/cddl1.php">CDDL 1.0</a></li>
<li><a href="http://opensource.org/licenses/cpl1.0.php">CPL 1.0</a></li>
<li><a href="http://opensource.org/licenses/eclipse-1.0.php">EPL 1.0</a></li>
<li><a href="http://opensource.org/licenses/ibmpl.php">IPL 1.0</a></li>
<li><a href="http://opensource.org/licenses/mozilla1.0.php">MPL 1.0</a> and <a href="http://opensource.org/licenses/mozilla1.1.php">MPL 1.1</a></li>
<li><a href="http://opensource.org/licenses/sunpublic.php">SPL 1.0</a></li>
</ul>
</p>
<p>For small amounts of source that is directly consumed by the ASF product
at runtime in source form, and for which that source is unlikely to be changed
anyway (say, by virtue of being specified by a standard), this action is
sufficient.  An example of this is the <a href="http://java.sun.com/dtd/web-facesconfig_1_0.dtd">web-facesconfig_1_0.dtd</a>, whose inclusion is mandated by the <a href="http://jcp.org/en/jsr/detail?id=127">JSR 127: JavaServer Faces</a> specification.</p>
<p>Code that is more substantial, more volatile, or not directly consumed at
runtime in <a href="#define-source">source</a> form may only be distributed in <a href="#define-binary">binary form</a>.</p>

<p>By including only the object/binary form, there is less exposed surface area of the third-party work from 
which a work might be derived; this addresses the <a href="#principle2">second guiding principle of this policy</a>.  
By attaching a prominent label to the distribution and requiring an explicit action by the user to get the 
reciprocally-licensed source, users are less likely to be unaware of restrictions significantly different from those
of the Apache License; this addresses the <a href="#principle4">fourth guiding principle of this policy</a>.
</p>
<p>
Although the source must not be included in Apache products, the NOTICE file, which is required to be included 
in each ASF distribution, <b>must point to the <a href="#define-source">source</a> form of the included binary</b> 
(more on that in the forthcoming "Receiving and Releasing Contributions" document).</p>
<p>Note that works written in a scripting language without a <a href="#define-binary">binary</a> form 
cannot be included in any ASF product under one of these licenses (see <a href="#transition">
Transition and Exceptions</a>).  In addition, C-based projects may have difficulty using works under these licenses since 
they would have to deal with platform-specific binaries, rather than just 
distributing <a href="#define-source">source</a> that can be built on most any platform.</p>
</div>
 
   <a name="category-x"><h4>Category X: Excluded Licenses</h4></a> 
 
<div class="section-content">
<p>The following licenses must not apply to any software within an Apache product,
whether in <a href="#define-source">source</a> or <a href="#define-binary">binary</a> form.  See <a href="#options">Options for Prohibited 
Works</a> for applicability to <a href="#options-systemrequirements">system requirements</a> or 
<a href="#options-optional">optional works</a> distributed elsewhere.</p>
<ul>
<li><a href="http://java.sun.com/products/jsse/LICENSE.html">BCL</a><a href="#transition-note">*</a></li>
<li><a href="http://www.gnu.org/software/classpath/license.html">Special exceptions to the GNU GPL (e.g. GNU Classpath)</a><a href="#transition-note">*</a></li>
<li><a href="http://opensource.org/licenses/gpl-license.php">GNU GPL</a></li>
<li><a href="http://opensource.org/licenses/lgpl-license.php">GNU LGPL</a><a href="#transition-note">*</a></li>
<li><a href="http://www.mozilla.org/MPL/NPL-1.0.html">NPL 1.0</a> and <a href="http://www.mozilla.org/MPL/NPL-1.1.html">NPL 1.1</a><a href="#transition-note">*</a></li>
<li><a href="http://opensource.org/licenses/qtpl.php">QPL</a></li>
<li><a href="http://opensource.org/licenses/sleepycat.php">Sleepycat License</a></li>
</ul>
<p><a name="transition-note"> </a><i>* see discussion of this in <a href="#transition">Transition and Exceptions</a></i></p>
</div>
</div>
</div>
           
   <a name="labeling"><h2>License Labeling Requirement</h2></a>

<div class="section-content">

   <a name="labeling-purpose"><h3>Purpose</h3></a>

<div class="section-content">
<p>This policy allows some terms within 
included licenses that go beyond the restrictions of the Apache License 
(see <a href="#criteria">License Criteria</a>).  Such allowance attempts to provide an 
appropriate compromise between the advantages of efficiency and 
familiarity achieved by reusing other open source works within Apache 
products and the need to continue to meet the licensing expectations of users of
Apache-branded products.  However, following the <a href="#principle4">fourth guiding principle
of this policy</a>, this compromise requires extra effort to ensure our 
users understand what they are getting.</p>
<p>The forthcoming policy on "Receiving and Releasing Contributions" will
describe how we keep users informed through the inclusion of all applicable 
license files and notices inside a distribution.  This labeling policy 
takes the extra step of alerting users of key licensing characteristics 
using a few easily visible labels on the download site and within the distribution itself.</p>
<p><i>The License Labeling Requirement goes into effect three months after the 
<a href="#effectivedate">effective date</a> of this policy.  This gives 
PMCs time to determine which labels apply to their releases and to insert 
the appropriate provided labels into their distribution and download pages.  
To minimize the effort required of PMCs by this labeling policy, the VP of 
Legal Affairs will provide a table mapping licenses to labels and a kit to 
make the effort of updating the download page comparable to that of adding an 
ApacheCon logo to a project's web site.</i></p>
</div>

   <a name="labeling-policy"><h3>Labeling Requirements</h3></a>

<div class="section-content">
<p>To help users quickly identify important characteristics of the collection of 
licenses that apply to an Apache product, a product-specific set of labels with a 
corresponding set of definitions will be included in all ASF download pages and 
<a href="#define-thirdpartylicense">third-party license</a> indexes within ASF distributions.  The download pages will also 
include a graphic representation of each label.  The Creative Commons licenses use 
a similar system to identify the key characteristics of each individual license; 
however, this system uses labels to identify characteristics of a <i>set of licenses</i> 
that apply to a specific product.</p>
<p>Below are the three label categories, reflecting three concerns our users may have 
about <a href="#define-thirdpartylicense">third-party licenses</a>.  Each category has two 
possible states or "labels".   The graphic version of each label is not 
yet available. <i>[Editorial Note: please volunteer (see <a href="#contact">contact info</a>) if you would like to design them.]</i>
</p>
 
   <a name="labeling-uniformity"><h4>License Uniformity</h4></a> 
 
<div class="section-content">
<ul>
<li><b>Single-License:</b> All works included within the product are licensed to 
    Apache users under the Apache License (v.2+).</li>
<br />
<li><b>Multi-Licensed:</b> While all code developed at the ASF is licensed under the 
    Apache License, one or more third-party works are licensed under other terms.  
    These terms may or may not include various attribution requirements, patent grants, 
    termination clauses, and reciprocity requirements.  However, all licenses covering any part of an Apache product meet the
    <a href="#criteria">ASF's third-party licensing criteria</a>.</li>
</ul>
</div>
 
   <a name="labeling-source"><h4>Source Access</h4></a> 
 
<div class="section-content">
<ul>
<li><b>Source Included:</b> The source distribution for the Apache product includes the complete 
   source for the entire product, including all third-party works.</li>
<br />
<li><b>Source Available:</b> The source distribution for the Apache product 
   does not include the source for some third-party works, but such source 
   is available online, as noted in the product's NOTICE file.</li>
<br />
</ul>
</div>
 
   <a name="labeling-reciprocity"><h4>License Reciprocity</h4></a> 
 
<div class="section-content">
<ul>
<li><b>No Reciprocity Required:</b> No part of the Apache product requires distribution of derivative works 
to be made available under the same license as the original work.</li>
<br />
<li><b>Reciprocity Required by some Components:</b> Some included third-party works are licensed under terms 
   that require distribution of derivative works to be made available under the same license as the original work.  
   See the Apache product's LICENSE file to find the applicable third-party licenses.</li>
</ul>
</div>
</div>
</div>
           
   <a name="options"><h2>Options for Prohibited Works</h2></a>

<div class="section-content">

   <a name="options-purpose"><h3>Purpose</h3></a>

<div class="section-content">
<p>The purpose of this part of the policy is to support the <a href="#principle3">third-guiding principle of this policy</a> 
by offering options for PMCs interested in <a href="#define-thirdpartywork">third-party works</a> that cannot be included in an ASF product 
<a href="#category-x">due to their license</a>.</p>
</div>

   <a name="options-philosophy"><h3>Philosophy</h3></a>

<div class="section-content">
<p>One of the <a href="#principles">guiding principles behind this policy</a> is to maintain 
the value and connotation of the Apache brand; therefore, <a href="#category-x">some licenses</a> are excluded from 
applying to any part of an Apache product.  However, there are two categories of software 
on which this policy places no licensing restrictions: <a href="#options-systemrequirements">system requirements (works used 
by the product)</a> and <a href="#options-optional">optional add-ons (works that use the product)</a>.</p>
</div>

   <a name="options-systemrequirements"><h3>System Requirements</h3></a>

<div class="section-content">
<p>
If a PMC wishes to build a product that takes a core dependency on some 
<a href="#define-thirdpartywork">third-party work</a> that is only available under an <a href="#category-x">excluded license</a>, 
the PMC might consider whether the work can be used as a system requirement, rather than an internal part of the product.  
The drawback to this approach is that every new system requirement narrows the 
potential user base for the product.  Each PMC is solely responsible for 
choosing an appropriate set of system requirements for its products; however, the 
following guidelines are recommended:
<ul>
<li>Clearly label each product's system requirements and their licenses on the main product page.</li>
<li>Consider the project's implicit/explicit charter and intention of the board resolution that created the project when determining how the system requirements will affect the users.</li>
<li>Provide a means, when practical, for users to substitute an alternative implementation for system requirements only available under <a href="#category-x">excluded licenses</a> (especially non-<a href="http://opensource.org/docs/definition.php">OSD licenses</a>).</li>
</ul>
</p>
</div>

   <a name="options-optional"><h3>Optional Add-ons</h3></a>

<div class="section-content">
<p>
If a PMC wishes to allow optional add-ons to enhance the functionality of 
the standard Apache product, the following options are available:
<ul>
<li>For add-ons under <a href="#category-a">authorized</a> <a href="#category-b">licenses</a>, the add-on could be distributed inside the product (see forthcoming policy on "Receiving and Releasing Contributions" for details on how and where to do this).</li>
<li>For add-ons under <a href="#category-x">excluded licenses</a>, the PMC may provide a link/reference on the product web site or within product documentation to some other web site that hosts such add-ons (e.g. a SF.net project or some third-party site dedicated to distributing add-ons for the Apache product) as long as it is made clear to users that the host site is not part of the Apache product nor endorsed by the ASF.</li>
<li>For add-ons under <a href="#category-x">excluded licenses</a>, the PMC may include a feature within the product that allows the user to obtain third-party add-ons if the feature also alerts the user of the associated license and makes clear to users that the host site is not part of the Apache product nor endorsed by the ASF.</li>
</ul>
</p>
</div>

   <a name="options-scenarios"><h3>Scenarios Involving Prohibited Works</h3></a>

<div class="section-content">
<p>The following scenarios provide more detail of what may and may not be done with 
<a href="#define-prohibitedwork">prohibited works</a> (defined as third-party works licensed under an  
<a href="#category-x">excluded license</a>).</p>
 
   <a name="options-inproduct"><h4>Inclusion within the product</h4></a> 
 
<div class="section-content">
<ul>
<li><a name="options-inproduct-mustnot1"> </a><b>YOU MUST NOT</b> include any portion of a <a href="#define-prohibitedwork">prohibited work</a> within the Apache product, 
     whether or not that work is considered required or optional.</li>
<br />
<li><a name="options-inproduct-may1"> </a><b>YOU MAY</b> include code within the Apache product necessary to achieve compatibility with a 
       <a href="#define-prohibitedwork">prohibited work</a> through the use of API calls, "bridge code", 
       or protocols, provided that the compatibility code was contributed under a 
       <a href="http://apache.org/licenses/#clas">CLA</a>.  However, any such code used for compatibility
       with a third-party work that is licensed under terms that violate <a href="#criterion2">criterion #2</a> 
       ("must not place restrictions on the distribution of independent works that simply use or contain the covered work."), 
       such as the GPL, requires review and explicit approval of both the PMC chair and the Legal Affairs officer.
       This review will ensure that the Apache product takes only the necessary steps to achieve compatibility.</li>
<br />
<li><a name="options-inproduct-may2"> </a><b>YOU MAY ALSO</b> include a feature within an Apache product that allows the user to explicitly choose to download
   an <a href="#options-optional">optional third-party add-on</a>, as long as that feature also alerts the user 
   of the associated license.</li>
</ul>
</div>
 
   <a name="options-distribution"><h4>Distribution</h4></a> 
 
<div class="section-content">
<ul>
<li><a name="options-distribution-mustnot1"> </a><b>YOU MUST NOT</b> distribute a <a href="#define-prohibitedwork">prohibited work</a> from an apache.org server.</li>
<br />
<li><a name="options-distribution-may1"> </a><b>YOU MAY</b> reference a <a href="#define-prohibitedwork">prohibited work</a> (e.g. with text or hyperlinks) from 
 an apache.org web page or identify the work as a <a href="#options-systemrequirements">system requirement</a>
 for the proper operation of the Apache product.</li>
</ul>
</div>
 
   <a name="options-pmcaction"><h4>PMC Actions</h4></a> 
 
<div class="section-content">
<ul>
<li><a name="options-pmcaction-mustnot1"> </a><b>YOU MUST NOT</b> modify, assemble, or release a <a href="#define-prohibitedwork">prohibited work</a> as an 
    action of an ASF PMC.</li>
<br />
<li><a name="options-pmcaction-may1"> </a><b>YOU MAY</b> independently develop, assemble, or release software under an <a href="#category-x">excluded license</a> 
    as an individual who happens to be an ASF committer/PMC member, but only when such action is 
    not identified as being associated with or sponsored by the ASF.</li>
</ul>
</div>
 
   <a name="options-build"><h4>Build Scripts</h4></a> 
 
<div class="section-content">
<ul>
<li><a name="options-build-mustnot1"> </a><b>YOU MUST NOT</b> distribute build scripts or documentation within an Apache product with the purpose of causing 
the default/standard build of an Apache product to include any part of a <a href="#define-prohibitedwork">prohibited work</a>.</li>
<br />
<li><a name="options-build-may1"> </a><b>YOU MAY</b> include within an Apache product a documented, non-default, build option to allow users to 
explicitly insert a <a href="#define-prohibitedwork">prohibited work</a> into a single <a href="#define-binary">binary</a> 
package with the Apache product code.</li>
<br />
<li><a name="options-build-may2"> </a><b>YOU MAY ALSO</b> include within an Apache product a documented, non-default, build option to allow users to
explicitly choose to validate, retrieve, or configure any <a href="#options-systemrequirements">system requirement</a> 
for an Apache product, provided that such option is not likely to be confused with the standard product build and that
any resulting retrieval of a <a href="#define-prohibitedwork">prohibited work</a> is accompanied by a clear identification 
of its associated license.</li>
</ul>
</div>
</div>
</div>

   <a name="transition"><h2>Transition and Exceptions</h2></a>

<div class="section-content">

   <a name="transition-purpose"><h3>Purpose</h3></a>

<div class="section-content">
<p>The purpose of this section is to describe the schedule by which PMCs are 
expected to transition through full compliance with this policy.  In addition, a 
special rule for incubating projects is established and possible authorized exceptions
are discussed.</p>
</div>

   <a name="transition-general"><h3>General Rule</h3></a>

<div class="section-content">
<p>
All <a href="#define-prohibitedwork">prohibited works</a> that are currently included in 
builds or releases must be removed from future versions by the earlier of:
<ul>
<li>one year from the <a href="#effectivedate">effective date</a> of this policy, or</li>
<li>the second major release of any ASF product.</li>
</ul>
</p>
<p>In addition, as of the <a href="#effectivedate">effective date</a> of this policy, <i>new</i> 
  <a href="#define-prohibitedwork">prohibited works</a> must not be added to any project build or distribution.
</p>
</div>

   <a name="transition-reevaluation"><h3>Reevaluation Checkpoint</h3></a>

<div class="section-content">
<p>For the following cases only, the application of the General Rule described 
above will be reevaluated in six months from the <a href="#effectivedate">effective date</a> of this policy:
<ul>
<li><a href="#transition-examples-npl">exclusion of the NPL 1.0 and 1.1 licenses</a></li>
<li>prohibition of the application of <a href="#category-b">Category B licenses</a> (for <a href="#define-binary">binary</a> 
only) to <a href="#transition-examples-javascript">JavaScript</a>, <a href="#transition-examples-xml">XML</a>, 
and other works lacking a <a href="#define-binary">binary</a> form</li>
</ul>
The result of such a reevaluation will either a) extend the time line, b) modify the policy to create permanent 
exceptions for these cases, or c) confirm the application of the General Rule 
(leaving no more than the remaining six months to remove all <a href="#define-prohibitedwork">prohibited works</a>).
</p>
</div>

   <a name="transition-incubator"><h3>Special Rule for Incubating Projects</h3></a>

<div class="section-content">
<p>
Since projects undergoing incubation are not officially endorsed by the ASF and 
are given an allowance to work out any remaining legal issues, a  
relaxed rule applies to these projects.  The intent of this rule is to allow 
existing open source projects already including <a href="#define-prohibitedwork">prohibited works</a> 
to start incubation and then work to remove the <a href="#define-prohibitedwork">prohibited works</a> from the product.</p>
<p>
In lieu of the General Rule above, the following rules apply to projects undergoing incubation:
<ul>
<li>Initial code for newly incubating projects may be covered by an <a href="#category-x">excluded license</a>, as long as the license is confirmed not to 
place licensing restrictions on code developed for the project under CLA contributions.  Either the V.P. of the 
Incubator Project or Legal Affairs V.P must make this determination.</li>
<li>After the initial code contribution, future additions to the incubating project must not include works under an <a href="#category-x">excluded license</a>.</li>
<li>Incubating projects must not distribute an official product release that includes works covered by an <a href="#category-x">excluded license</a>.</li>
</ul>
</p>
</div>

   <a name="transition-labeling"><h3>Exceptions and the License Labeling Requirement</h3></a>

<div class="section-content">
<p>
Should PMCs start implementing the <a href="#labeling">License Labeling Requirement</a> 
before <a href="#define-prohibitedwork">prohibited works</a> have been removed from their releases (whether major 
or minor releases), a special label will be needed for each label category that 
some <a href="#define-thirdpartylicense">third-party license</a> violates.  (e.g. "Transitional Exception: One or more 
works is not available under an open source license", with an associated image label having a 
big red "X" over the typical label category image plus product-specific text 
describing the work, the issue, and the expected date of compliance.)
</p>
</div>

   <a name="transition-examples"><h3>Applicability to excluded licenses used today (or licenses that have been considered for use)</h3></a>

<div class="section-content">
 
   <a name="transition-examples-bcl"><h4>BCL</h4></a> 
 
<div class="section-content">
<p>
The Binary Code License falls far short of the <a href="http://opensource.org/docs/definition.php">Open Source Definition</a>, thereby 
violating the first criterion for license approval.  All BCL-licensed 
works currently included in ASF products must be removed before the 
earlier of one year or two major releases (see the General Rule above).  
PMCs with BCL-licensed works are encouraged to use this time to request 
copyright owners of such works to consider also licensing under an authorized 
license (<a href="#category-a">Category A</a> or <a href="#category-a">Category B</a>), such as the CDDL.  
Another option for some products may be to move the BCL-licensed work to a system requirement that is not 
included in the product.
</p>
</div>
 
   <a name="transition-examples-npl"><h4>NPL</h4></a> 
 
<div class="section-content">
<p>
The NPL is simply the MPL (which is allowed under <a href="#category-b">Category B</a>) plus amendments 
that are specific to Netscape.  Unfortunately, these amendments allow 
"Netscape" (now part of Time Warner) to avoid the <a href="#define-reciprocal">reciprocity</a> requirement that all other 
licensees must adhere to.  This disqualifies the license from meeting <a href="http://opensource.org/docs/definition.php#5">Open 
Source Definition #5</a> ("No Discrimination Against Persons or Groups").  While this is a clear violation 
of the <a href="#criterion1">first license criterion</a>, it is unlikely to be a significant practical 
concern for users of Apache products that include an NPL <a href="#define-binary">binary</a>.  Therefore, the 
NPL is currently listed as an <a href="#category-x">excluded license</a>, but this exclusion will be reevaluated in six months.
</p>
</div>
 
   <a name="transition-examples-xml"><h4>XML and Text Configuration files under Category B licenses</h4></a> 
 
<div class="section-content">
<p>
The current license policy only allows <a href="#define-source">source</a> files to 
be included under a <a href="#category-a">Category A license</a>, not a <a href="#category-b">Category B license</a> 
(<a href="#define-binary">binary</a> only).  Therefore, XML and text files covered by a <a href="#category-b">Category B license</a> 
cannot be included in an Apache product.  Whether this places a significant burden on PMCs will be reevaluated in six months.
</p>
</div>
 
   <a name="transition-examples-javascript"><h4>JavaScript/ECMAScript libraries under Category B licenses</h4></a> 
 
<div class="section-content">
<p>
As AJAX-related functionality becomes more popular, there may be a 
demand for JavaScript libraries, which are only available in <a href="#define-source">source</a> form.  The current license 
policy allows such code to be included when covered by a <a href="#category-a">Category A license</a> 
(authorized for <a href="#define-source">source</a> and <a href="#define-binary">binary</a>), but not a <a href="#category-b">Category B license</a> 
(<a href="#define-binary">binary</a> only).  Whether there is an overwhelming need for such <a href="#category-b">Category B-licensed</a> JavaScript 
libraries to be included in the product will be reevaluated in six months.
</p>
</div>
 
   <a name="transition-examples-lgpl"><h4>LGPL</h4></a> 
 
<div class="section-content">
<p>
The LGPL v2.1 is ineligible from being a <a href="#category-b">Category B license</a> (a category that 
includes the MPL, CPL, EPL, and CDDL) primarily due to the restrictions it places on larger works, violating the
<a href="#criterion3">third license criterion</a>.  Therefore, LGPL v2.1-licensed works must not be included in Apache products, although they may be listed 
as <a href="#options-systemrequirements">system requirements</a> or distributed elsewhere as <a href="#options-optional">optional works</a>.  
</p>
</div>
 
   <a name="transition-examples-gpl-exception"><h4>Special exceptions to the GNU GPL</h4></a> 
 
<div class="section-content">
<p>
Some copyright holders have licensed their works under the GPL with special exceptions.  Although these
exceptions may appear to be addressing the restrictions disallowed by the ASF's first and second license
criteria, the exceptions may only apply to software not "derived from or based on" the covered work.  
The references terms defined in the GPL that include works that "use" or "contain" the work.  Therefore,
software under these exceptions is generally not allowed for inclusion within an Apache product.  
PMCs may, however, choose to allow such works to be system requirements of an Apache product, 
provided a review by the ASF Legal Affairs officer and PMC chair determine no part of the product is copied 
from or derived from the GPL/exception-licensed work other than what is strictly required to achieve compatibility.  
See details for <a href="#options-inproduct">inclusions within the product</a> that are related to excluded licenses.
</p>
</div>
</div>
</div>
          
   <a name="appendix"><h2>Appendix</h2></a>
    
<div class="section-content">
    
       <a name="define"><h3>Definitions</h3></a>
    
    <dl>
     <di><a name="define-binary"> </a>
      <dt><u>binary</u></dt>
      <dd>a form of the work not typically used for making modifications, including executables, object code, and Java class files</dd>
     </di>
     <br />
     <di><a name="define-largerwork"> </a>
      <dt><u>larger work</u></dt>
      <dd>a work which combines the third-party work or portions thereof with code not governed by the terms of the third-party work's license (borrowed from the MPL/CDDL definition)</dd>
     </di>
     <br />
     <di><a name="define-nonreciprocal"> </a>
      <dt><u>nonreciprocal</u></dt>
      <dd>allowing distribution of modifications and derivative works to be licensed under any terms that do not cause the distributor
          to violate the original license</dd>
     </di>
     <br />
     <di><a name="define-prohibitedwork"> </a>
      <dt><u>prohibited work</u></dt>
      <dd>a third-party work only available under an excluded (Category X) license</dd>
     </di>
     <br />
     <di><a name="define-reciprocal"> </a>
      <dt><u>reciprocal</u></dt>
      <dd>requiring that the distribution of modifications or derivative works be made available under the same license as the original work</dd>
     </di>
     <br />
     <di><a name="define-source"> </a>
      <dt><u>source</u></dt>
      <dd>the preferred form of the work for making modifications <i>(borrowed from the GPL's definition)</i></dd>
     </di>
     <br />
     <di><a name="define-thirdpartywork"> </a>
      <dt><u>third-party work</u></dt>
      <dd>any work that has not been contributed to the ASF under a Contributor License Agreement</dd>
     </di>
     <br />
     <di><a name="define-thirdpartylicense"> </a>
      <dt><u>third-party license</u></dt>
      <dd>the license applying to a third-party work</dd>
     </di>
    </dl>
<br />
<br />
<br />
<br />
</div>

   <a name="contact"><h3>Contact Info for Questions and Feedback</h3></a>

<div class="section-content">
<p>
For questions or feedback on this policy, please send mail to the <a href="http://www.apache.org/foundation/mailinglists.html#foundation-legal">legal-discuss mailing list</a>.
</p>
</div>
</body>
