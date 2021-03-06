| Class | Champs | Description |
|:---|:---|:---|
|[Application](/javascript/api/excel/excel.application)|[Calculate (calculationType : Excel. CalculationType)](/javascript/api/excel/excel.application#calculate-calculationtype-)|Recalcule tous les classeurs actuellement ouverts dans Excel.|
||[calculationMode](/javascript/api/excel/excel.application#calculationmode)|Renvoie le mode de calcul utilisé dans le classeur, tel que défini par les constantes dans Excel. CalculationMode.|
|[Binding](/javascript/api/excel/excel.binding)|[getRange()](/javascript/api/excel/excel.binding#getrange--)|Renvoie la plage représentée par la liaison.|
||[getTable()](/javascript/api/excel/excel.binding#gettable--)|Renvoie le tableau représenté par la liaison.|
||[getText()](/javascript/api/excel/excel.binding#gettext--)|Renvoie le texte représenté par la liaison.|
||[id](/javascript/api/excel/excel.binding#id)|Représente l’identificateur de liaison.|
||[type](/javascript/api/excel/excel.binding#type)|Renvoie le type de la liaison.|
|[BindingCollection](/javascript/api/excel/excel.bindingcollection)|[getItem(id: string)](/javascript/api/excel/excel.bindingcollection#getitem-id-)|Obtient un objet de liaison par ID.|
||[getItemAt(index: number)](/javascript/api/excel/excel.bindingcollection#getitemat-index-)|Obtient un objet de liaison en fonction de sa position dans le tableau d’éléments.|
||[count](/javascript/api/excel/excel.bindingcollection#count)|Renvoie le nombre de liaisons de la collection.|
||[items](/javascript/api/excel/excel.bindingcollection#items)|Obtient l’élément enfant chargé dans cette collection de sites.|
|[Chart](/javascript/api/excel/excel.chart)|[delete()](/javascript/api/excel/excel.chart#delete--)|Supprime l’objet de graphique.|
||[height](/javascript/api/excel/excel.chart#height)|Indique la hauteur, exprimée en points, de l’objet Chart.|
||[left](/javascript/api/excel/excel.chart#left)|La distance, en points, entre le côté gauche du graphique et l’origine de la feuille de calcul.|
||[name](/javascript/api/excel/excel.chart#name)|Cette énumération spécifie le nom d’un objet Chart.|
||[ordonné](/javascript/api/excel/excel.chart#axes)|Représente les axes du graphique.|
||[dataLabels](/javascript/api/excel/excel.chart#datalabels)|Représente les étiquettes des données sur le graphique.|
||[format](/javascript/api/excel/excel.chart#format)|Regroupe les propriétés de format de la zone de graphique.|
||[Legend](/javascript/api/excel/excel.chart#legend)|Représente la légende du graphique.|
||[series](/javascript/api/excel/excel.chart#series)|Représente une série ou une collection de séries dans le graphique.|
||[title](/javascript/api/excel/excel.chart#title)|Cette énumération spécifie le titre du graphique spécifié, y compris le texte, la visibilité, la position et la mise en forme du titre.|
||[setData (sourceData : Range, seriesBy ?: Excel. ChartSeriesBy)](/javascript/api/excel/excel.chart#setdata-sourcedata--seriesby-)|Redéfinit les données sources du graphique.|
||[setPosition (startCell : \| chaîne de plage, endCell ?: \| chaîne de plage)](/javascript/api/excel/excel.chart#setposition-startcell--endcell-)|Positionne le graphique par rapport aux cellules dans la feuille de calcul.|
||[top](/javascript/api/excel/excel.chart#top)|Indique la distance, en points, entre le bord supérieur de l’objet et le haut de ligne 1 (dans une feuille de calcul) ou le haut de la zone de graphique (dans un graphique).|
||[width](/javascript/api/excel/excel.chart#width)|Indique la largeur, exprimée en points, de l’objet Chart.|
|[ChartAreaFormat](/javascript/api/excel/excel.chartareaformat)|[fill](/javascript/api/excel/excel.chartareaformat#fill)|Représente le format de remplissage d’un objet, qui comprend des informations de mise en forme d’arrière-plan.|
||[police](/javascript/api/excel/excel.chartareaformat#font)|Représente les attributs de police (nom de la police, taille de police, couleur, etc.) de l’objet.|
|[ChartAxes](/javascript/api/excel/excel.chartaxes)|[categoryAxis](/javascript/api/excel/excel.chartaxes#categoryaxis)|Représente l’axe des abscisses d’un graphique.|
||[seriesAxis](/javascript/api/excel/excel.chartaxes#seriesaxis)|Représente l’axe de séries d’un graphique 3D.|
||[valueAxis](/javascript/api/excel/excel.chartaxes#valueaxis)|Représente l’axe des ordonnées.|
|[ChartAxis](/javascript/api/excel/excel.chartaxis)|[majorUnit](/javascript/api/excel/excel.chartaxis#majorunit)|Représente l’intervalle entre deux graduations principales.|
||[maximum](/javascript/api/excel/excel.chartaxis#maximum)|Représente la valeur maximale sur l’axe des ordonnées.|
||[minimum](/javascript/api/excel/excel.chartaxis#minimum)|Représente la valeur minimale sur l’axe des ordonnées.|
||[minorUnit](/javascript/api/excel/excel.chartaxis#minorunit)|Représente l’intervalle entre deux graduations secondaires.|
||[format](/javascript/api/excel/excel.chartaxis#format)|Représente la mise en forme d’un objet de graphique, à savoir le format des lignes et de la police.|
||[majorGridlines](/javascript/api/excel/excel.chartaxis#majorgridlines)|Renvoie un objet de quadrillage qui représente les lignes de quadrillage principal de l’axe spécifié.|
||[minorGridlines](/javascript/api/excel/excel.chartaxis#minorgridlines)|Renvoie un objet de quadrillage qui représente les lignes de quadrillage secondaire de l’axe spécifié.|
||[title](/javascript/api/excel/excel.chartaxis#title)|Représente le titre de l’axe.|
|[ChartAxisFormat](/javascript/api/excel/excel.chartaxisformat)|[police](/javascript/api/excel/excel.chartaxisformat#font)|Spécifie les attributs de police (nom de police, taille de police, couleur, etc.) pour un élément d’axe de graphique.|
||[line](/javascript/api/excel/excel.chartaxisformat#line)|Indique la mise en forme des lignes de graphique.|
|[ChartAxisTitle](/javascript/api/excel/excel.chartaxistitle)|[format](/javascript/api/excel/excel.chartaxistitle#format)|Cette énumération spécifie la mise en forme du titre de l’axe du graphique.|
||[text](/javascript/api/excel/excel.chartaxistitle#text)|Indique le titre de l’axe.|
||[visible](/javascript/api/excel/excel.chartaxistitle#visible)|Indique si le titre de l’axe est visibile.|
|[ChartAxisTitleFormat](/javascript/api/excel/excel.chartaxistitleformat)|[police](/javascript/api/excel/excel.chartaxistitleformat#font)|Spécifie les attributs de police du titre de l’axe du graphique, tels que le nom de la police, la taille de police, la couleur, etc.|
|[ChartCollection](/javascript/api/excel/excel.chartcollection)|[Add (type : Excel. ChartType, sourceData : Range, seriesBy ?: Excel. ChartSeriesBy)](/javascript/api/excel/excel.chartcollection#add-type--sourcedata--seriesby-)|Crée un graphique.|
||[getItem(name: string)](/javascript/api/excel/excel.chartcollection#getitem-name-)|Extrait un graphique à l’aide de son nom.|
||[getItemAt(index: number)](/javascript/api/excel/excel.chartcollection#getitemat-index-)|Extrait un graphique en fonction de sa position dans la collection.|
||[count](/javascript/api/excel/excel.chartcollection#count)|Renvoie le nombre de graphiques dans la feuille de calcul.|
||[items](/javascript/api/excel/excel.chartcollection#items)|Obtient l’élément enfant chargé dans cette collection de sites.|
|[ChartDataLabelFormat](/javascript/api/excel/excel.chartdatalabelformat)|[fill](/javascript/api/excel/excel.chartdatalabelformat#fill)|Représente le format de remplissage de l’étiquette de données.|
||[police](/javascript/api/excel/excel.chartdatalabelformat#font)|Représente les attributs de police (nom de la police, taille de police, couleur, etc.) d’une étiquette de données de graphique.|
|[ChartDataLabels](/javascript/api/excel/excel.chartdatalabels)|[position](/javascript/api/excel/excel.chartdatalabels#position)|Valeur DataLabelPosition qui représente la position de l’étiquette de données.|
||[format](/javascript/api/excel/excel.chartdatalabels#format)|Cette énumération spécifie le format des étiquettes de données de graphique, qui inclut la mise en forme de remplissage et de police.|
||[para](/javascript/api/excel/excel.chartdatalabels#separator)|Chaîne représentant le séparateur utilisé pour les étiquettes de données d’un graphique.|
||[showBubbleSize](/javascript/api/excel/excel.chartdatalabels#showbubblesize)|Indique si la taille de la bulle des étiquettes de données est visible.|
||[showCategoryName](/javascript/api/excel/excel.chartdatalabels#showcategoryname)|Indique si le nom de catégorie de l’étiquette de données est visible.|
||[ShowLegendKey,](/javascript/api/excel/excel.chartdatalabels#showlegendkey)|Indique si la légende de l’étiquette de données est visible.|
||[showPercentage](/javascript/api/excel/excel.chartdatalabels#showpercentage)|Indique si le pourcentage de l’étiquette de données est visible.|
||[showSeriesName](/javascript/api/excel/excel.chartdatalabels#showseriesname)|Indique si le nom de série des étiquettes de données est visible.|
||[showValue](/javascript/api/excel/excel.chartdatalabels#showvalue)|Indique si la valeur de l’étiquette de données est visible.|
|[ChartFill](/javascript/api/excel/excel.chartfill)|[clear()](/javascript/api/excel/excel.chartfill#clear--)|Supprime la couleur de remplissage d’un élément de graphique.|
||[setSolidColor(color: string)](/javascript/api/excel/excel.chartfill#setsolidcolor-color-)|Définit le format de remplissage d’un élément de graphique sur une couleur unie.|
|[ChartFont](/javascript/api/excel/excel.chartfont)|[bold](/javascript/api/excel/excel.chartfont#bold)|Représente le format de police Gras.|
||[color](/javascript/api/excel/excel.chartfont#color)|Représentation de code de couleur HTML de la couleur du texte (par exemple, #FF0000 représente le rouge).|
||[italic](/javascript/api/excel/excel.chartfont#italic)|Représente le format de police Italique.|
||[name](/javascript/api/excel/excel.chartfont#name)|Nom de la police (par exemple, « Calibri »)|
||[size](/javascript/api/excel/excel.chartfont#size)|Taille de la police (par exemple, 11)|
||[underline](/javascript/api/excel/excel.chartfont#underline)|Type de soulignement appliqué à la police.|
|[ChartGridlines](/javascript/api/excel/excel.chartgridlines)|[format](/javascript/api/excel/excel.chartgridlines#format)|Représente le format du quadrillage de graphique.|
||[visible](/javascript/api/excel/excel.chartgridlines#visible)|Indique si le quadrillage de l’axe est visible.|
|[ChartGridlinesFormat](/javascript/api/excel/excel.chartgridlinesformat)|[line](/javascript/api/excel/excel.chartgridlinesformat#line)|Représente le format des lignes du graphique.|
|[ChartLegend](/javascript/api/excel/excel.chartlegend)|[overlay](/javascript/api/excel/excel.chartlegend#overlay)|Indique si la légende du graphique doit se chevaucher avec le corps principal du graphique.|
||[position](/javascript/api/excel/excel.chartlegend#position)|Indique la position de la légende sur le graphique.|
||[format](/javascript/api/excel/excel.chartlegend#format)|Représente le format d’une légende de graphique, à savoir le format du remplissage et de la police.|
||[visible](/javascript/api/excel/excel.chartlegend#visible)|Indique si l’ChartLegend est visible.|
|[ChartLegendFormat](/javascript/api/excel/excel.chartlegendformat)|[fill](/javascript/api/excel/excel.chartlegendformat#fill)|Représente le format de remplissage d’un objet, qui comprend des informations de mise en forme d’arrière-plan.|
||[police](/javascript/api/excel/excel.chartlegendformat#font)|Représente les attributs de police, tels que le nom de la police, la taille de police, la couleur, etc.|
|[ChartLineFormat](/javascript/api/excel/excel.chartlineformat)|[clear()](/javascript/api/excel/excel.chartlineformat#clear--)|Désactiver le format de ligne d’un élément de graphique.|
||[color](/javascript/api/excel/excel.chartlineformat#color)|Code couleur HTML qui représente la couleur des lignes dans le graphique.|
|[ChartPoint](/javascript/api/excel/excel.chartpoint)|[format](/javascript/api/excel/excel.chartpoint#format)|Regroupe les propriétés de format d’un point d’un graphique.|
||[value](/javascript/api/excel/excel.chartpoint#value)|Renvoie la valeur d’un point du graphique.|
|[ChartPointFormat](/javascript/api/excel/excel.chartpointformat)|[fill](/javascript/api/excel/excel.chartpointformat#fill)|Représente le format de remplissage d’un graphique, qui inclut des informations de mise en forme de l’arrière-plan.|
|[ChartPointsCollection](/javascript/api/excel/excel.chartpointscollection)|[getItemAt(index: number)](/javascript/api/excel/excel.chartpointscollection#getitemat-index-)|Extrait un point en fonction de sa position dans la série.|
||[count](/javascript/api/excel/excel.chartpointscollection#count)|Renvoie le nombre de points de graphique dans la série.|
||[items](/javascript/api/excel/excel.chartpointscollection#items)|Obtient l’élément enfant chargé dans cette collection de sites.|
|[ChartSeries](/javascript/api/excel/excel.chartseries)|[name](/javascript/api/excel/excel.chartseries#name)|Cette énumération spécifie le nom d’une série dans un graphique.|
||[format](/javascript/api/excel/excel.chartseries#format)|Représente le format d’une série de graphique, à savoir le format de remplissage et des lignes.|
||[pointe](/javascript/api/excel/excel.chartseries#points)|Renvoie une collection de tous les points de la série.|
|[ChartSeriesCollection](/javascript/api/excel/excel.chartseriescollection)|[getItemAt(index: number)](/javascript/api/excel/excel.chartseriescollection#getitemat-index-)|Extrait une série en fonction de sa position dans la collection.|
||[count](/javascript/api/excel/excel.chartseriescollection#count)|Renvoie le nombre de séries de la collection.|
||[items](/javascript/api/excel/excel.chartseriescollection#items)|Obtient l’élément enfant chargé dans cette collection de sites.|
|[ChartSeriesFormat](/javascript/api/excel/excel.chartseriesformat)|[fill](/javascript/api/excel/excel.chartseriesformat#fill)|Représente le format de remplissage d’une série du graphique, qui comprend les informations de mise en forme d’arrière-plan.|
||[line](/javascript/api/excel/excel.chartseriesformat#line)|Représente le format des lignes.|
|[ChartTitle](/javascript/api/excel/excel.charttitle)|[overlay](/javascript/api/excel/excel.charttitle#overlay)|Indique si le titre du graphique chevauche le graphique.|
||[format](/javascript/api/excel/excel.charttitle#format)|Représente le format du titre d’un graphique, à savoir le format de remplissage et de la police.|
||[text](/javascript/api/excel/excel.charttitle#text)|Spécifie le texte du titre du graphique.|
||[visible](/javascript/api/excel/excel.charttitle#visible)|Indique si le titre du graphique est visibile.|
|[ChartTitleFormat](/javascript/api/excel/excel.charttitleformat)|[fill](/javascript/api/excel/excel.charttitleformat#fill)|Représente le format de remplissage d’un objet, qui comprend des informations de mise en forme d’arrière-plan.|
||[police](/javascript/api/excel/excel.charttitleformat#font)|Représente les attributs de police (nom de la police, taille de police, couleur, etc.) pour un objet.|
|[NamedItem](/javascript/api/excel/excel.nameditem)|[getRange()](/javascript/api/excel/excel.nameditem#getrange--)|Renvoie l’objet de plage qui est associé au nom.|
||[name](/javascript/api/excel/excel.nameditem#name)|Nom de l’objet.|
||[type](/javascript/api/excel/excel.nameditem#type)|Cette énumération spécifie le type de la valeur renvoyée par la formule du nom.|
||[value](/javascript/api/excel/excel.nameditem#value)|Représente la valeur calculée par la formule du nom.|
||[visible](/javascript/api/excel/excel.nameditem#visible)|Indique si l’objet est visible.|
|[NamedItemCollection](/javascript/api/excel/excel.nameditemcollection)|[getItem(name: string)](/javascript/api/excel/excel.nameditemcollection#getitem-name-)|Obtient un objet NamedItem à l’aide de son nom.|
||[items](/javascript/api/excel/excel.nameditemcollection#items)|Obtient l’élément enfant chargé dans cette collection de sites.|
|[Range](/javascript/api/excel/excel.range)|[Effacer (applyTo ? : Excel.ClearApplyTo)](/javascript/api/excel/excel.range#clear-applyto-)|Supprime les valeurs et les propriétés de format, de remplissage, de bordure, etc. de la plage.|
||[supprimer (Maj : Excel. DeleteShiftDirection)](/javascript/api/excel/excel.range#delete-shift-)|Supprime les cellules associées à la plage.|
||[formulas](/javascript/api/excel/excel.range#formulas)|Représente la formule dans le style de notation A1.|
||[formulasLocal](/javascript/api/excel/excel.range#formulaslocal)|Représente la formule en notation A1, en utilisant le langage et les paramètres de format de nombre régionaux de l’utilisateur.|
||[getBoundingRect (anotherRange : chaîne de plage \| )](/javascript/api/excel/excel.range#getboundingrect-anotherrange-)|Renvoie le plus petit objet de plage qui englobe les plages données.|
||[getCell(row: number, column: number)](/javascript/api/excel/excel.range#getcell-row--column-)|Renvoie l’objet de plage qui contient une cellule donnée sur la base des numéros de ligne et de colonne.|
||[getColumn(column: number)](/javascript/api/excel/excel.range#getcolumn-column-)|Obtient une colonne contenue dans la plage.|
||[getEntireColumn()](/javascript/api/excel/excel.range#getentirecolumn--)|Obtient un objet qui représente la colonne entière de la plage (par exemple, si la plage actuelle représente les cellules « B4 : E11 », `getEntireColumn` qu’il s’agit d’une plage qui représente les colonnes « B :E »).|
||[getEntireRow()](/javascript/api/excel/excel.range#getentirerow--)|Obtient un objet qui représente la ligne entière de la plage (par exemple, si la plage actuelle représente les cellules « B4 : E11 », `GetEntireRow` qu’il s’agit d’une plage qui représente les lignes « 4:11 »).|
||[getIntersection (anotherRange : chaîne de plage \| )](/javascript/api/excel/excel.range#getintersection-anotherrange-)|Obtient l’objet de plage qui représente l’intersection rectangulaire des plages données.|
||[getLastCell()](/javascript/api/excel/excel.range#getlastcell--)|Obtient la dernière cellule de la plage.|
||[getLastColumn()](/javascript/api/excel/excel.range#getlastcolumn--)|Obtient la dernière colonne de la plage.|
||[getLastRow()](/javascript/api/excel/excel.range#getlastrow--)|Obtient la dernière ligne de la plage.|
||[getOffsetRange(rowOffset: number, columnOffset: number)](/javascript/api/excel/excel.range#getoffsetrange-rowoffset--columnoffset-)|Obtient un objet qui représente une plage décalée par rapport à la plage spécifiée.|
||[getRow(row: number)](/javascript/api/excel/excel.range#getrow-row-)|Obtient une ligne contenue dans la plage.|
||[Insérer (Maj : Excel. InsertShiftDirection)](/javascript/api/excel/excel.range#insert-shift-)|Insère une cellule ou une plage de cellules dans la feuille de calcul à la place d’une plage donnée et décale les autres cellules pour libérer de l’espace.|
||[numberFormat](/javascript/api/excel/excel.range#numberformat)|Représente le code de format de nombre d’Excel pour la plage donnée.|
||[adresse](/javascript/api/excel/excel.range#address)|Spécifie la référence de plage en style a1.|
||[addressLocal](/javascript/api/excel/excel.range#addresslocal)|Cette énumération spécifie la référence de plage pour la plage spécifiée dans la langue de l’utilisateur.|
||[cellCount](/javascript/api/excel/excel.range#cellcount)|Indique le nombre de cellules de la plage.|
||[NbreColonnes](/javascript/api/excel/excel.range#columncount)|Indique le nombre total de colonnes de la plage.|
||[columnIndex](/javascript/api/excel/excel.range#columnindex)|Indique le numéro de colonne de la première cellule de la plage.|
||[format](/javascript/api/excel/excel.range#format)|Renvoie un objet format qui encapsule la police, le remplissage, les bordures, l’alignement et d’autres propriétés de la plage.|
||[Stopp](/javascript/api/excel/excel.range#rowcount)|Renvoie le nombre total de lignes de la plage.|
||[rowIndex](/javascript/api/excel/excel.range#rowindex)|Renvoie le numéro de ligne de la première cellule de la plage.|
||[text](/javascript/api/excel/excel.range#text)|Valeurs de texte de la plage spécifiée.|
||[valueTypes](/javascript/api/excel/excel.range#valuetypes)|Cette énumération spécifie le type de données dans chaque cellule.|
||[worksheet](/javascript/api/excel/excel.range#worksheet)|Feuille de calcul contenant la plage.|
||[select()](/javascript/api/excel/excel.range#select--)|Sélectionne la plage spécifiée dans l’interface utilisateur d’Excel.|
||[values](/javascript/api/excel/excel.range#values)|Représente les valeurs brutes de la plage spécifiée.|
|[RangeBorder](/javascript/api/excel/excel.rangeborder)|[color](/javascript/api/excel/excel.rangeborder#color)|Code couleur HTML qui représente la couleur de la ligne de bordure, au format #RRGGBB (par exemple : « FFA500 ») ou sous forme de couleur HTML nommée (par exemple, « orange »).|
||[sideIndex](/javascript/api/excel/excel.rangeborder#sideindex)|Valeur constante qui indique un côté spécifique de la bordure.|
||[style](/javascript/api/excel/excel.rangeborder#style)|L’une des constantes de style de ligne déterminant le style de ligne de la bordure.|
||[weight](/javascript/api/excel/excel.rangeborder#weight)|Spécifie l'épaisseur de la bordure autour d'une plage.|
|[RangeBorderCollection](/javascript/api/excel/excel.rangebordercollection)|[getItem (index : Excel. BorderIndex)](/javascript/api/excel/excel.rangebordercollection#getitem-index-)|Obtient un objet de bordure à l’aide de son nom.|
||[getItemAt(index: number)](/javascript/api/excel/excel.rangebordercollection#getitemat-index-)|Obtient un objet de bordure à l’aide de son indice.|
||[count](/javascript/api/excel/excel.rangebordercollection#count)|Nombre d’objets de bordure de la collection.|
||[items](/javascript/api/excel/excel.rangebordercollection#items)|Obtient l’élément enfant chargé dans cette collection de sites.|
|[RangeFill](/javascript/api/excel/excel.rangefill)|[clear()](/javascript/api/excel/excel.rangefill#clear--)|Réinitialise l’arrière-plan de la plage.|
||[color](/javascript/api/excel/excel.rangefill#color)|Code couleur HTML représentant la couleur de l’arrière-plan, de la #RRGGBB de formulaire (par exemple, « FFA500 ») ou sous forme de couleur HTML nommée (par exemple, « orange »)|
|[RangeFont](/javascript/api/excel/excel.rangefont)|[bold](/javascript/api/excel/excel.rangefont#bold)|Représente le format de police Gras.|
||[color](/javascript/api/excel/excel.rangefont#color)|Représentation de code de couleur HTML de la couleur du texte (par exemple, #FF0000 représente le rouge).|
||[italic](/javascript/api/excel/excel.rangefont#italic)|Spécifie l’État italique de la police.|
||[name](/javascript/api/excel/excel.rangefont#name)|Nom de la police (par exemple, "Calibri").|
||[size](/javascript/api/excel/excel.rangefont#size)|Taille de police|
||[underline](/javascript/api/excel/excel.rangefont#underline)|Type de soulignement appliqué à la police.|
|[RangeFormat](/javascript/api/excel/excel.rangeformat)|[horizontalAlignment](/javascript/api/excel/excel.rangeformat#horizontalalignment)|Représente l’alignement horizontal de l’objet spécifié.|
||[Borders](/javascript/api/excel/excel.rangeformat#borders)|Collection d’objets de bordure qui s’appliquent à l’ensemble de la plage.|
||[fill](/javascript/api/excel/excel.rangeformat#fill)|Renvoie l’objet de remplissage défini sur la plage globale.|
||[police](/javascript/api/excel/excel.rangeformat#font)|Renvoie l’objet de police défini sur l’ensemble de la plage.|
||[verticalAlignment](/javascript/api/excel/excel.rangeformat#verticalalignment)|Représente l’alignement vertical de l’objet spécifié.|
||[wrapText](/javascript/api/excel/excel.rangeformat#wraptext)|Indique si Excel renvoie le texte à la ligne dans l’objet.|
|[Table](/javascript/api/excel/excel.table)|[delete()](/javascript/api/excel/excel.table#delete--)|Supprime le tableau.|
||[getDataBodyRange()](/javascript/api/excel/excel.table#getdatabodyrange--)|Obtient l’objet de plage associé au corps de données du tableau.|
||[getHeaderRowRange()](/javascript/api/excel/excel.table#getheaderrowrange--)|Obtient l’objet de plage associé à la ligne d’en-tête du tableau.|
||[getRange()](/javascript/api/excel/excel.table#getrange--)|Renvoie l’objet de plage associé à l’intégralité du tableau.|
||[getTotalRowRange()](/javascript/api/excel/excel.table#gettotalrowrange--)|Renvoie l’objet de plage associé à la ligne de total du tableau.|
||[name](/javascript/api/excel/excel.table#name)|Nom du tableau.|
||[colonnes](/javascript/api/excel/excel.table#columns)|Représente une collection de toutes les colonnes du tableau.|
||[id](/javascript/api/excel/excel.table#id)|Renvoie une valeur qui permet d’identifier le tableau dans un classeur donné.|
||[rows](/javascript/api/excel/excel.table#rows)|Représente une collection de toutes les lignes du tableau.|
||[showHeaders](/javascript/api/excel/excel.table#showheaders)|Indique si la ligne d’en-tête est visible.|
||[ShowTotals,](/javascript/api/excel/excel.table#showtotals)|Indique si la ligne total est visible.|
||[style](/javascript/api/excel/excel.table#style)|Valeur de constante qui représente le style du tableau.|
|[TableCollection](/javascript/api/excel/excel.tablecollection)|[Add (Address : Range \| String, hasHeaders : Boolean)](/javascript/api/excel/excel.tablecollection#add-address--hasheaders-)|Crée un tableau.|
||[getItem(key: string)](/javascript/api/excel/excel.tablecollection#getitem-key-)|Obtient un tableau à l’aide de son nom ou de son ID.|
||[getItemAt(index: number)](/javascript/api/excel/excel.tablecollection#getitemat-index-)|Obtient un tableau en fonction de sa position dans la collection.|
||[count](/javascript/api/excel/excel.tablecollection#count)|Renvoie le nombre de tableaux dans le classeur.|
||[items](/javascript/api/excel/excel.tablecollection#items)|Obtient l’élément enfant chargé dans cette collection de sites.|
|[TableColumn](/javascript/api/excel/excel.tablecolumn)|[delete()](/javascript/api/excel/excel.tablecolumn#delete--)|Supprime la colonne du tableau.|
||[getDataBodyRange()](/javascript/api/excel/excel.tablecolumn#getdatabodyrange--)|Obtient l’objet de plage associé au corps de données de la colonne.|
||[getHeaderRowRange()](/javascript/api/excel/excel.tablecolumn#getheaderrowrange--)|Obtient l’objet de plage associé à la ligne d’en-tête de la colonne.|
||[getRange()](/javascript/api/excel/excel.tablecolumn#getrange--)|Renvoie l’objet de plage associé à l’intégralité de la colonne.|
||[getTotalRowRange()](/javascript/api/excel/excel.tablecolumn#gettotalrowrange--)|Obtient l’objet de plage associé à la ligne de total de la colonne.|
||[name](/javascript/api/excel/excel.tablecolumn#name)|Spécifie le nom de la colonne de la table.|
||[id](/javascript/api/excel/excel.tablecolumn#id)|Renvoie une clé unique qui identifie la colonne du tableau.|
||[index](/javascript/api/excel/excel.tablecolumn#index)|Renvoie le numéro d’indice de la colonne dans la collection de colonnes du tableau.|
||[values](/javascript/api/excel/excel.tablecolumn#values)|Représente les valeurs brutes de la plage spécifiée.|
|[TableColumnCollection](/javascript/api/excel/excel.tablecolumncollection)|[Add (index ?: Number, Values ?: Array<Array<Boolean \| String \| Number>> \| Boolean \| String \| Number, Name ?: String)](/javascript/api/excel/excel.tablecolumncollection#add-index--values--name-)|Ajoute une nouvelle colonne au tableau.|
||[getItem (Key : valeur numérique \| )](/javascript/api/excel/excel.tablecolumncollection#getitem-key-)|Obtient un objet de colonne par son nom ou son ID.|
||[getItemAt(index: number)](/javascript/api/excel/excel.tablecolumncollection#getitemat-index-)|Obtient une colonne en fonction de sa position dans la collection.|
||[count](/javascript/api/excel/excel.tablecolumncollection#count)|Renvoie le nombre de colonnes du tableau.|
||[items](/javascript/api/excel/excel.tablecolumncollection#items)|Obtient l’élément enfant chargé dans cette collection de sites.|
|[TableRow](/javascript/api/excel/excel.tablerow)|[delete()](/javascript/api/excel/excel.tablerow#delete--)|Supprime la ligne du tableau.|
||[getRange()](/javascript/api/excel/excel.tablerow#getrange--)|Renvoie l’objet de plage associé à la ligne entière.|
||[index](/javascript/api/excel/excel.tablerow#index)|Renvoie le numéro d’indice de la ligne dans la collection de lignes du tableau.|
||[values](/javascript/api/excel/excel.tablerow#values)|Représente les valeurs brutes de la plage spécifiée.|
|[TableRowCollection](/javascript/api/excel/excel.tablerowcollection)|[Add (index ?: Number, Values ?: Array<Array<Boolean \| String \| Number>> \| Boolean \| String \| Number)](/javascript/api/excel/excel.tablerowcollection#add-index--values-)|Ajoute une ou plusieurs lignes dans le tableau.|
||[getItemAt(index: number)](/javascript/api/excel/excel.tablerowcollection#getitemat-index-)|Obtient une ligne en fonction de sa position dans la collection.|
||[count](/javascript/api/excel/excel.tablerowcollection#count)|Renvoie le nombre de lignes du tableau.|
||[items](/javascript/api/excel/excel.tablerowcollection#items)|Obtient l’élément enfant chargé dans cette collection de sites.|
|[Workbook](/javascript/api/excel/excel.workbook)|[getSelectedRange ()](/javascript/api/excel/excel.workbook#getselectedrange--)|Obtient la plage unique actuellement sélectionnée du classeur.|
||[application](/javascript/api/excel/excel.workbook#application)|Représente l’instance de l’application Excel qui contient ce classeur.|
||[bindings](/javascript/api/excel/excel.workbook#bindings)|Représente une collection de liaisons appartenant au classeur.|
||[zone](/javascript/api/excel/excel.workbook#names)|Représente une collection d’éléments nommés portant sur le classeur (appelés plages et constantes).|
||[emplois](/javascript/api/excel/excel.workbook#tables)|Représente une collection de tableaux associés au classeur.|
||[feuilles](/javascript/api/excel/excel.workbook#worksheets)|Représente une collection de feuilles de calcul associées au classeur.|
|[Worksheet](/javascript/api/excel/excel.worksheet)|[activate()](/javascript/api/excel/excel.worksheet#activate--)|Active la feuille de calcul dans l’interface utilisateur Excel.|
||[delete()](/javascript/api/excel/excel.worksheet#delete--)|Supprime la feuille de calcul du classeur.|
||[getCell(row: number, column: number)](/javascript/api/excel/excel.worksheet#getcell-row--column-)|Renvoie l’objet de plage qui contient une cellule donnée sur la base des numéros de ligne et de colonne.|
||[getRange (Address ?: String)](/javascript/api/excel/excel.worksheet#getrange-address-)|Obtient l’objet de plage, représentant un seul bloc de cellules rectangulaires, spécifié par l’adresse ou le nom.|
||[name](/javascript/api/excel/excel.worksheet#name)|Nom complet de la feuille de calcul.|
||[position](/javascript/api/excel/excel.worksheet#position)|Position de la feuille de calcul au sein du classeur (sur une base zéro).|
||[bulles](/javascript/api/excel/excel.worksheet#charts)|Renvoie une collection de graphiques qui font partie de la feuille de calcul.|
||[id](/javascript/api/excel/excel.worksheet#id)|Renvoie une valeur qui permet d’identifier la feuille de calcul de façon unique dans un classeur donné.|
||[emplois](/javascript/api/excel/excel.worksheet#tables)|Collection de tableaux qui font partie de la feuille de calcul.|
||[visibility](/javascript/api/excel/excel.worksheet#visibility)|Visibilité de la feuille de calcul.|
|[WorksheetCollection](/javascript/api/excel/excel.worksheetcollection)|[Add (Name ?: String)](/javascript/api/excel/excel.worksheetcollection#add-name-)|Ajoute une nouvelle feuille de calcul au classeur.|
||[getActiveWorksheet()](/javascript/api/excel/excel.worksheetcollection#getactiveworksheet--)|Obtient la feuille de calcul active du classeur.|
||[getItem(key: string)](/javascript/api/excel/excel.worksheetcollection#getitem-key-)|Obtient un objet de feuille de calcul à l’aide de son nom ou de son ID.|
||[items](/javascript/api/excel/excel.worksheetcollection#items)|Obtient l’élément enfant chargé dans cette collection de sites.|
