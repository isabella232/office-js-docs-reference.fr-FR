| Class | Champs | Description |
|:---|:---|:---|
|[InsertSlideOptions](/javascript/api/powerpoint/powerpoint.insertslideoptions)|[mise en forme](/javascript/api/powerpoint/powerpoint.insertslideoptions#formatting)|Indique la mise en forme à utiliser lors de l’insertion d’une diapositive.|
||[sourceSlideIds](/javascript/api/powerpoint/powerpoint.insertslideoptions#sourceslideids)|Cette énumération spécifie les diapositives de la présentation source qui seront insérées dans la présentation en cours.|
||[targetSlideId](/javascript/api/powerpoint/powerpoint.insertslideoptions#targetslideid)|Indique où seront insérées les nouvelles diapositives dans la présentation.|
|[Presentation](/javascript/api/powerpoint/powerpoint.presentation)|[insertSlidesFromBase64 (base64File : chaîne, Options ?: PowerPoint. InsertSlideOptions)](/javascript/api/powerpoint/powerpoint.presentation#insertslidesfrombase64-base64file--options-)|Insère les diapositives spécifiées à partir d’une présentation dans la présentation active.|
||[celles](/javascript/api/powerpoint/powerpoint.presentation#slides)|Renvoie une collection ordonnée de diapositives dans la présentation.|
|[Slide](/javascript/api/powerpoint/powerpoint.slide)|[delete()](/javascript/api/powerpoint/powerpoint.slide#delete--)|Supprime la diapositive de la présentation.|
||[id](/javascript/api/powerpoint/powerpoint.slide#id)|Obtient l’ID unique de la diapositive.|
|[SlideCollection](/javascript/api/powerpoint/powerpoint.slidecollection)|[getCount()](/javascript/api/powerpoint/powerpoint.slidecollection#getcount--)|Obtient le nombre de diapositives de la collection.|
||[getItem(key: string)](/javascript/api/powerpoint/powerpoint.slidecollection#getitem-key-)|Obtient une diapositive à l’aide de son ID unique.|
||[getItemAt(index: number)](/javascript/api/powerpoint/powerpoint.slidecollection#getitemat-index-)|Obtient une diapositive à l’aide de son index de base zéro dans la collection.|
||[getItemOrNullObject(id: string)](/javascript/api/powerpoint/powerpoint.slidecollection#getitemornullobject-id-)|Obtient une diapositive à l’aide de son ID unique.|
||[items](/javascript/api/powerpoint/powerpoint.slidecollection#items)|Obtient l’élément enfant chargé dans cette collection de sites.|
