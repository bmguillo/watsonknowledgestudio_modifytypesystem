## Deploy WKS ML Annotator Model After Type System Modification 

## Learning Objectives

The objective of this tutorial is part 2 of a previous tutorial which is to edit the type system, continue with previous annotations, train/evaluate the ML annotator model then re-deploy the model to NLU to extract patterns, keywords from unstructured text. This use case is specific for the automotive industry but can be used for other domains as well.

## Prerequisites

- IBM Cloud account: If you do not have an IBM Cloud account, you can create an account [here](https://cloud.ibm.com/)
- Provision a Watson Knowledge Studio [instance](https://cloud.ibm.com/catalog/services/knowledge-studio?hideTours=true&?cm_sp=WatsonPlatform-WatsonPlatform-_-OnPageNavCTA-IBMWatson_Discovery-_-Watson_Developer_Website) within IBM Cloud & creation of a workspace.
- Basic knowledge of Watson Knowledge Studio process workflow & creation of roles by viewing [docs](https://cloud.ibm.com/docs/services/watson-knowledge-studio?topic=watson-knowledge-studio-wks_tutintro#wks_tokenizer).

## Estimated Time

It is recommended to annotate a variety of a large set of documents for greater accuracy however, estimated times are as follows:20 docs = 2 hours , 10 docs = 1 hour, 5 docs = 30 min and a small sample size will be used for this exercise.

## Challenge

Customers may have a need to modify the type system that they have created after they have deployed their model to NLU as a continuous training/testing practice for greater optimization and accuracy of the model.

## Modification of Type System for Continuous Training-Adding an Entity Type Person

![test](https://github.com/bmguillo/watsonknowledgestudio_modifytypesystem/blob/master/img/1_addentitytypesizing.png)

## Create New Annotation Set for Existing Annotated Documents

![test](https://github.com/bmguillo/watsonknowledgestudio_modifytypesystem/blob/master/img/2_createannotationsetsresize.png)
![test](https://github.com/bmguillo/watsonknowledgestudio_modifytypesystem/blob/master/img/3a_modificationtypesystemresize.png)
![test](https://github.com/bmguillo/watsonknowledgestudio_modifytypesystem/blob/master/img/3b_documentlistresize.png)

## Create New Annotation Task to Pick up New Entity Type & Annotation Continuation

![test](https://github.com/bmguillo/watsonknowledgestudio_modifytypesystem/blob/master/img/4-modificationtypetaskresize.png)
![test](https://github.com/bmguillo/watsonknowledgestudio_modifytypesystem/blob/master/img/5_inprogressannotateresize.png)
![test](https://github.com/bmguillo/watsonknowledgestudio_modifytypesystem/blob/master/img/6_selectannotationdocresize.png)

## Continuation of Annotation – Add Mention of Entity Type Person

![test](https://github.com/bmguillo/watsonknowledgestudio_modifytypesystem/blob/master/img/7-MENTIONTYPERESIZE.png)

## Submit All Annotations for Review & Accept as Ground Truth

![test](https://github.com/bmguillo/watsonknowledgestudio_modifytypesystem/blob/master/img/7_groundtruthresize.png)
![test](https://github.com/bmguillo/watsonknowledgestudio_modifytypesystem/blob/master/img/8_submitannotationsresize.png)

## Train & Evaluate

![test](https://github.com/bmguillo/watsonknowledgestudio_modifytypesystem/blob/master/img/8_trainingtestblindsetsresize.png)

## Train & Evaluate

![test](https://github.com/bmguillo/watsonknowledgestudio_modifytypesystem/blob/master/img/9_mlmodelevalresize.png)

## Take Snapshot ( if pleased with results and plan on doing workspace revisions later, re-training and re-evaluation of model)

![test](https://github.com/bmguillo/watsonknowledgestudio_modifytypesystem/blob/master/img/10_snapshotscreenresize.png)

## Deploy to NLU 

![test](https://github.com/bmguillo/watsonknowledgestudio_modifytypesystem/blob/master/img/10_deploymodelinforesize.png)
![test](https://github.com/bmguillo/watsonknowledgestudio_modifytypesystem/blob/master/img/12_twomodelsdeployedtoNLUresize.png)

## Apply Type System Updates (Quick Method)

- After modification of type system by adding entity type, edit existing annotation task, then click [apply type system](https://cloud.ibm.com/docs/services/watson-knowledge-studio?topic=watson-knowledge-studio-improve-ml#improve-ml) updates and proceed with remainder of steps above

