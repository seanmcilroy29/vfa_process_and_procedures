# GitHub Flow
<table>
  <caption>GitHub Workflow</caption>
  <thead>
    <tr>
	    <th>Branch</th>
	    <th>Description</th>
    </tr>
  </thead>
  <tbody>
    <tr>
	    <td><i>Rel vX.Y.Z</i></td>
      <td>Release-tags contain all the different versions of the Technical Specifications that have been approved by the Working Group and ratified by the Technical Steering Committee. The name of the release tag will follow Semantic versioning principles. </td>
   </tr>
    <tr>
	    <td><i>publication</i></td>
      <td>This branch contains the latest version of the Technical Specification approved by the Working Group, the Organization Team and ratified by the Technical Steering Committee. Its content will be moved into a release-tag, to preserve the content of the version. </td>
   </tr>
   <tr>
	    <td><i>agreement</i></td>
	    <td>This branch contains a draft specification that are stable, approved by the Working Group but still under development. This branch SHALL NOT contain any feature that is not part of the delivery plan. </td>
   </tr>
   <tr>
	    <td><i>feature-branch-x</i></td>
	    <td>Feature branches are dedicated to develop specific features, concepts, sections, etc. These branches are not stable, content is developed here until it is stable and completed. At that point it can be merged into the "staging" branch. </td>
   </tr>
  </tbody>
</table>

<figure>
	<img src="img/vfa-git-flow.svg" alt="VFA GitHub Flow">
	<figcaption>VFA GitHub Flow</figcaption>
</figure>

## GitHub [VFA Membership and Appointment Access Rights](https://github.com/volumetricformat/the_way_we_work/tree/Initial_proposal/Support_Documentation)

## GitHub Publication
There are at least three different options to publish content using GitHub:
<figure>
	<img src="img/roe_private-vs-public.svg" alt="Private vs Public">
	<figcaption>Private vs Public</figcaption>
</figure>
