---
title: "IFilePathProvider"
second_title: "Aspose.Cells for Java API Reference"
description: "Represents the exported file path provider."
type: docs
url: "/java/com.aspose.cells/ifilepathprovider/"
source_url: "https://reference.aspose.com/cells/java/com.aspose.cells/ifilepathprovider/"
generated_from: "online-reference"
fetched_at: "2026-06-16T11:51:17+00:00"
---
```
public interface IFilePathProvider
```

Represents the exported file path provider.

## Methods {#methods}

| Method | Description |
| --- | --- |
| [getFullName(String sheetName)](#getFullName-java.lang.String-) | Gets the full path of the file by Worksheet name when exporting Worksheet to HTML separately. |

### getFullName(String sheetName) {#getFullName-java.lang.String-}

```
public abstract String getFullName(String sheetName)
```

Gets the full path of the file by Worksheet name when exporting Worksheet to HTML separately. So the references among the Worksheets can be exported correctly.

**Parameters:**

| Parameter | Type | Description |
| --- | --- | --- |
| sheetName | java.lang.String | Worksheet name |

**Returns:**
java.lang.String - the full path of the file
