---
title: "Introducción a las tablas temporales con versión del sistema | Microsoft Docs"
ms.custom:
- SQL2016_New_Updated
ms.date: 03/28/2016
ms.prod: sql-server-2016
ms.reviewer: 
ms.suite: 
ms.technology:
- dbe-tables
ms.tgt_pltfrm: 
ms.topic: get-started-article
ms.assetid: d431f216-82cf-4d97-825e-bb35d3d53a45
caps.latest.revision: 12
author: CarlRabeler
ms.author: carlrab
manager: jhubbard
ms.translationtype: Human Translation
ms.sourcegitcommit: f3481fcc2bb74eaf93182e6cc58f5a06666e10f4
ms.openlocfilehash: 0318f2a574bcdb2f02016fc6d865252deb6fef4a
ms.contentlocale: es-es
ms.lasthandoff: 06/22/2017

---
# <a name="getting-started-with-system-versioned-temporal-tables"></a>Introducción a las tablas temporales con versión del sistema
[!INCLUDE[tsql-appliesto-ss2016-asdb-xxxx-xxx_md](../../includes/tsql-appliesto-ss2016-asdb-xxxx-xxx-md.md)]

  Según el escenario, puede crear nuevas tablas temporales de versionamiento del sistema o modificar las existentes incorporando atributos temporales al esquema de tabla existente.   
Cuando se modifican los datos de la tabla temporal, el sistema crea un historial de versiones de forma transparente para las aplicaciones y los usuarios finales. Por ello, trabajar con tablas temporales con versión del sistema no requiere ningún cambio en la forma en la que tabla se modifica o cómo se consulta el estado más reciente (real) de los datos.   
Además de DML y consultas convencionales, las tablas temporales también proporcionan formas sencillas y prácticas de obtener detalles a través de la sintaxis de Transact-SQL extendida.   
Todas las tablas con versión del sistema tienen una tabla de historial asignada pero es completamente transparente para los usuarios a menos que desean optimizar el rendimiento de la carga de trabajo o el espacio de almacenamiento creando índices adicionales o eligiendo distintas opciones de almacenamiento.    
El siguiente diagrama muestra el flujo de trabajo típico con tablas temporales con versión del sistema:   
![Introducción a las tablas temporales](../../relational-databases/tables/media/getting-started-with-temporal.png "Getting Started with Temporal")  
  
 Este tema se divide en los siguientes 5 temas secundarios:  
  
-   [Creación de una tabla temporal con control de versiones del sistema](../../relational-databases/tables/creating-a-system-versioned-temporal-table.md)  
  
-   [Modificación de los datos de una tabla temporal con control de versiones del sistema](../../relational-databases/tables/modifying-data-in-a-system-versioned-temporal-table.md)  
  
-   [Consulta de los datos de una tabla temporal con control de versiones del sistema](../../relational-databases/tables/querying-data-in-a-system-versioned-temporal-table.md)  
  
-   [Cambiar el esquema de una tabla temporal con control de versiones del sistema](../../relational-databases/tables/changing-the-schema-of-a-system-versioned-temporal-table.md)  
  
-   [Detención del control de versiones en una tabla temporal con control de versiones](../../relational-databases/tables/stopping-system-versioning-on-a-system-versioned-temporal-table.md)  
  
## <a name="did-this-article-help-you-were-listening"></a>¿Le ayudó este artículo? Le escuchamos  
 ¿Qué información está buscando? ¿La encontró? Escuchamos sus comentarios para mejorar el contenido. Envíe sus comentarios a [sqlfeedback@microsoft.com](mailto:sqlfeedback@microsoft.com?subject=Your%20feedback%20about%20the%20Getting%20Started%20with%20System-Versioned%20Temporal%20Tables%20page)  
  
## <a name="see-also"></a>Vea también  
 [Tablas temporales](../../relational-databases/tables/temporal-tables.md)   
 [Comprobaciones de coherencia del sistema de la tabla temporal](../../relational-databases/tables/temporal-table-system-consistency-checks.md)   
 [Creación de particiones con tablas temporales](../../relational-databases/tables/partitioning-with-temporal-tables.md)   
 [Limitaciones y consideraciones de las tablas temporales](../../relational-databases/tables/temporal-table-considerations-and-limitations.md)   
 [Seguridad de la tabla temporal](../../relational-databases/tables/temporal-table-security.md)   
 [Administración de la retención de datos históricos en las tablas temporales con versiones del sistema](../../relational-databases/tables/manage-retention-of-historical-data-in-system-versioned-temporal-tables.md)   
 [Tablas temporales con control de versiones del sistema con tablas con optimización para memoria](../../relational-databases/tables/system-versioned-temporal-tables-with-memory-optimized-tables.md)   
 [Funciones y vistas de metadatos de la tabla temporal](../../relational-databases/tables/temporal-table-metadata-views-and-functions.md)  
  
  

