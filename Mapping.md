# Mapping in Datamapper
Mapping is a feature to map the source and target data. Here are the few highlights about the Mapping.

* Adding multiple sources and targets are allowed.
* Data can be added from API link, files can be directly uploaded from local system.
* Drag and Drop of the files are supported.
* Maximum allowed file size is 500 KB.
* Auto mapping is supported for simillar coloumn names.
* Manual mapping is supported for any custom mapping.

## Create Mapping

Mapping can be created from multiple places, the most common scenerio is once the collection is created and you explore that collection you will get an option to create a new mapping. Also, from the home page you can create it from mapping and then create option.

1. To create mapping directly from the collection, click on the Create a new mapping under the collection name.

    ![](media/create-new-mapping.png)
   
2. Under the **Add mapping Details** tab, choose the collection name where you want to add the map and then provide the name for your map for **Name your map**, you can also add the description for this mapping under your selected collection.
3. Now, click on the Next button.

    ![](media/add-mapping-details.png)

4. Under **Upload and edit schemas** tab, add the source and target using any supported method, here we will upload the schema using API URL, you can also do it by upload/drag-drop the supported file types.

   ![](media/upload-schema.png)

5. To add the source, paste the API link from where you want to download the file and the click on download from the entered URL.

   ![](media/add-source.png)

6. Select the defination you want to import and then click on the **Create**.

   ![](media/create-source-deffination.png)

7. Simmilarly, you can add the target, provide the target API link or upload the file from your computer.

   ![](media/add-target.png)
   
8. Select the defination you want to import for the target and click on **Create**.

    ![](media/target-defination.png)

9. Once the source and target is added you can click on the eye icon under source and target and preview the schema.

    ![](media/eye-preview-schema.png)

10. Once you load the preview schema, you can see the data in a structured way. You can see **Reqd**, **Type**, **Property** etc. If you want you can edit the schema as well here.
11. Here lets edit the **Category** property name to **Cat** and then click on **Apply**. You can edit the other items as well like description and example.

    ![](media/edit-schema.png)

12. You can click on the cross icon on the top left corner to close the **Viewing Pet** screen.

13. Now, click on the **Next** to proceed with the source to target mapping.

    ![](media/stot1.png)
    
14. On **Save mapping** window, you can click on the **Auto Map & Save** to map the mapping automatically. Also, you can click on **Preview mapping** and update the mapping manually.

    ![](media/preview-mapping.png)

15. You can also remove the mapping by clicking on the target object and then click on teh ellepses and select remove all mapping.

16. Once you are done with the mapping, click on the **Apply and Save Mapping**.

    ![](media/apply-mapping.png)

17. Now, click on **Save Mapping**.

    ![](media/save-mapping.png)

18. You can generate the code using the **Code Generator**, code can be generated for supported programming languages i.e. Java (Experimental), Java Script (Experimental), C#, Java and Java Script. You can click on Generate Code icon and then select programming language of your choice. Once the code is generated you can copy it or download it.

    ![](media/generate-code.png)

    

   

