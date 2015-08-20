Richfaces custom tag based on Richfaces 3.3.3.Final extendedDataTable, but without drag-and-drop script (significantly reduces html produced by the component).

Example of usage

```
<ui:composition xmlns="http://www.w3.org/1999/xhtml"
    xmlns:a4j="http://richfaces.org/a4j"
    xmlns:customRich="http://labs.jboss.com/jbossrichfaces/ui/extendedDataTableWODND">
<html>
<body>

<a4j:loadScript src="resource:///org/richfaces/renderkit/html/scripts/extended-data-table-WODND.js"/>

<a4j:form>
<customRich:extendedDataTableWODND ...></customRich:extendedDataTableWODND>
</a4j:form>
</body>
</html>
</ui:composition>
```


You can download compiled tag jar in Downloads section or build yourself using maven

```
mvn clean install
```