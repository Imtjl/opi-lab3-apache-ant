.
├── build.dtd
├── build.xml
├── interactive-graph-ui
│   ├── build
│   │   ├── classes
│   │   │   ├── com
│   │   │   │   └── worthant
│   │   │   │       ├── CommaToDotConverter.class
│   │   │   │       └── jsfgraph
│   │   │   │           ├── CoordinateHandlerBean.class
│   │   │   │           ├── db
│   │   │   │           │   ├── DAOFactory.class
│   │   │   │           │   ├── JPAUtils.class
│   │   │   │           │   ├── ResultDAO.class
│   │   │   │           │   └── ResultDAOImpl.class
│   │   │   │           ├── entity
│   │   │   │           │   ├── ResultEntity$ResultEntityBuilder.class
│   │   │   │           │   └── ResultEntity.class
│   │   │   │           ├── RCoordinateBean.class
│   │   │   │           ├── ResultsControllerBean.class
│   │   │   │           ├── utils
│   │   │   │           │   └── AreaChecker.class
│   │   │   │           ├── XCoordinateBean.class
│   │   │   │           └── YCoordinateBean.class
│   │   │   ├── db.cfg
│   │   │   └── META-INF
│   │   │       └── persistence.xml
│   │   └── webapp
│   │       ├── error-pages
│   │       │   ├── 404.jsp
│   │       │   ├── 500.jsp
│   │       │   └── 503.jsp
│   │       ├── index.xhtml
│   │       ├── main.xhtml
│   │       ├── resources
│   │       │   ├── images
│   │       │   │   ├── favicon.png
│   │       │   │   ├── github.png
│   │       │   │   ├── hit.svg
│   │       │   │   ├── home.jpg
│   │       │   │   ├── main.jpg
│   │       │   │   ├── middle.jpg
│   │       │   │   └── portal.png
│   │       │   ├── js
│   │       │   │   ├── canvas-setup.js
│   │       │   │   ├── index.js
│   │       │   │   ├── main.js
│   │       │   │   └── utils.js
│   │       │   └── styles
│   │       │       ├── main.css
│   │       │       └── tw.css
│   │       └── WEB-INF
│   │           ├── classes
│   │           │   ├── com
│   │           │   │   └── worthant
│   │           │   │       ├── CommaToDotConverter.class
│   │           │   │       └── jsfgraph
│   │           │   │           ├── CoordinateHandlerBean.class
│   │           │   │           ├── db
│   │           │   │           │   ├── DAOFactory.class
│   │           │   │           │   ├── JPAUtils.class
│   │           │   │           │   ├── ResultDAO.class
│   │           │   │           │   └── ResultDAOImpl.class
│   │           │   │           ├── entity
│   │           │   │           │   ├── ResultEntity$ResultEntityBuilder.class
│   │           │   │           │   └── ResultEntity.class
│   │           │   │           ├── RCoordinateBean.class
│   │           │   │           ├── ResultsControllerBean.class
│   │           │   │           ├── utils
│   │           │   │           │   └── AreaChecker.class
│   │           │   │           ├── XCoordinateBean.class
│   │           │   │           └── YCoordinateBean.class
│   │           │   ├── db.cfg
│   │           │   └── META-INF
│   │           │       └── persistence.xml
│   │           ├── faces-config.xml
│   │           ├── lib
│   │           │   ├── checker-qual-3.31.0.jar
│   │           │   ├── jakarta.annotation-api-2.1.1.jar
│   │           │   ├── jakarta.faces-api-4.0.1.jar
│   │           │   ├── jakarta.persistence-api-3.0.0.jar
│   │           │   ├── logback-classic-1.2.9.jar
│   │           │   ├── logback-core-1.2.9.jar
│   │           │   ├── lombok-1.18.30.jar
│   │           │   ├── org.eclipse.persistence.asm-9.1.0.jar
│   │           │   ├── org.eclipse.persistence.core-3.0.2.jar
│   │           │   ├── org.eclipse.persistence.jpa-3.0.2.jar
│   │           │   ├── org.eclipse.persistence.jpa.jpql-3.0.2.jar
│   │           │   ├── postgresql-42.6.0.jar
│   │           │   ├── primefaces-12.0.0.jar
│   │           │   └── slf4j-api-1.7.32.jar
│   │           └── web.xml
│   ├── deploy.sh
│   ├── interactive-graph-ui.war
│   ├── lib
│   │   ├── checker-qual-3.31.0.jar
│   │   ├── jakarta.annotation-api-2.1.1.jar
│   │   ├── jakarta.faces-api-4.0.1.jar
│   │   ├── jakarta.persistence-api-3.0.0.jar
│   │   ├── logback-classic-1.2.9.jar
│   │   ├── logback-core-1.2.9.jar
│   │   ├── lombok-1.18.30.jar
│   │   ├── org.eclipse.persistence.asm-9.1.0.jar
│   │   ├── org.eclipse.persistence.core-3.0.2.jar
│   │   ├── org.eclipse.persistence.jpa-3.0.2.jar
│   │   ├── org.eclipse.persistence.jpa.jpql-3.0.2.jar
│   │   ├── postgresql-42.6.0.jar
│   │   ├── primefaces-12.0.0.jar
│   │   └── slf4j-api-1.7.32.jar
│   ├── mvnw
│   ├── mvnw.cmd
│   ├── package.json
│   ├── package-lock.json
│   ├── pom.xml
│   ├── postcss.config.js
│   ├── README.md
│   ├── README_RU.md
│   ├── resources
│   │   ├── graph.png
│   │   └── logo.png
│   ├── src
│   │   └── main
│   │       ├── java
│   │       │   └── com
│   │       │       └── worthant
│   │       │           ├── CommaToDotConverter.java
│   │       │           └── jsfgraph
│   │       │               ├── CoordinateHandlerBean.java
│   │       │               ├── db
│   │       │               │   ├── DAOFactory.java
│   │       │               │   ├── JPAUtils.java
│   │       │               │   ├── ResultDAOImpl.java
│   │       │               │   └── ResultDAO.java
│   │       │               ├── entity
│   │       │               │   └── ResultEntity.java
│   │       │               ├── RCoordinateBean.java
│   │       │               ├── ResultsControllerBean.java
│   │       │               ├── utils
│   │       │               │   └── AreaChecker.java
│   │       │               ├── XCoordinateBean.java
│   │       │               └── YCoordinateBean.java
│   │       ├── resources
│   │       │   ├── db.cfg
│   │       │   └── META-INF
│   │       │       └── persistence.xml
│   │       └── webapp
│   │           ├── error-pages
│   │           │   ├── 404.jsp
│   │           │   ├── 500.jsp
│   │           │   └── 503.jsp
│   │           ├── index.xhtml
│   │           ├── main.xhtml
│   │           ├── resources
│   │           │   ├── images
│   │           │   │   ├── favicon.png
│   │           │   │   ├── github.png
│   │           │   │   ├── hit.svg
│   │           │   │   ├── home.jpg
│   │           │   │   ├── main.jpg
│   │           │   │   ├── middle.jpg
│   │           │   │   └── portal.png
│   │           │   ├── js
│   │           │   │   ├── canvas-setup.js
│   │           │   │   ├── index.js
│   │           │   │   ├── main.js
│   │           │   │   └── utils.js
│   │           │   └── styles
│   │           │       ├── main.css
│   │           │       └── tw.css
│   │           └── WEB-INF
│   │               ├── faces-config.xml
│   │               └── web.xml
│   ├── tailwind.config.js
│   ├── target
│   │   ├── classes
│   │   │   ├── com
│   │   │   │   └── worthant
│   │   │   │       ├── CommaToDotConverter.class
│   │   │   │       └── jsfgraph
│   │   │   │           ├── CoordinateHandlerBean.class
│   │   │   │           ├── db
│   │   │   │           │   ├── DAOFactory.class
│   │   │   │           │   ├── JPAUtils.class
│   │   │   │           │   ├── ResultDAO.class
│   │   │   │           │   └── ResultDAOImpl.class
│   │   │   │           ├── entity
│   │   │   │           │   ├── ResultEntity$ResultEntityBuilder.class
│   │   │   │           │   └── ResultEntity.class
│   │   │   │           ├── RCoordinateBean.class
│   │   │   │           ├── ResultsControllerBean.class
│   │   │   │           ├── utils
│   │   │   │           │   └── AreaChecker.class
│   │   │   │           ├── XCoordinateBean.class
│   │   │   │           └── YCoordinateBean.class
│   │   │   ├── db.cfg
│   │   │   └── META-INF
│   │   │       └── persistence.xml
│   │   ├── generated-sources
│   │   │   └── annotations
│   │   ├── interactive-graph-ui-1.0-SNAPSHOT
│   │   │   ├── error-pages
│   │   │   │   ├── 404.jsp
│   │   │   │   ├── 500.jsp
│   │   │   │   └── 503.jsp
│   │   │   ├── index.xhtml
│   │   │   ├── main.xhtml
│   │   │   ├── META-INF
│   │   │   ├── resources
│   │   │   │   ├── images
│   │   │   │   │   ├── favicon.png
│   │   │   │   │   ├── github.png
│   │   │   │   │   ├── hit.svg
│   │   │   │   │   ├── home.jpg
│   │   │   │   │   ├── main.jpg
│   │   │   │   │   ├── middle.jpg
│   │   │   │   │   └── portal.png
│   │   │   │   ├── js
│   │   │   │   │   ├── canvas-setup.js
│   │   │   │   │   ├── index.js
│   │   │   │   │   ├── main.js
│   │   │   │   │   └── utils.js
│   │   │   │   └── styles
│   │   │   │       ├── main.css
│   │   │   │       └── tw.css
│   │   │   └── WEB-INF
│   │   │       ├── classes
│   │   │       │   ├── com
│   │   │       │   │   └── worthant
│   │   │       │   │       ├── CommaToDotConverter.class
│   │   │       │   │       └── jsfgraph
│   │   │       │   │           ├── CoordinateHandlerBean.class
│   │   │       │   │           ├── db
│   │   │       │   │           │   ├── DAOFactory.class
│   │   │       │   │           │   ├── JPAUtils.class
│   │   │       │   │           │   ├── ResultDAO.class
│   │   │       │   │           │   └── ResultDAOImpl.class
│   │   │       │   │           ├── entity
│   │   │       │   │           │   ├── ResultEntity$ResultEntityBuilder.class
│   │   │       │   │           │   └── ResultEntity.class
│   │   │       │   │           ├── RCoordinateBean.class
│   │   │       │   │           ├── ResultsControllerBean.class
│   │   │       │   │           ├── utils
│   │   │       │   │           │   └── AreaChecker.class
│   │   │       │   │           ├── XCoordinateBean.class
│   │   │       │   │           └── YCoordinateBean.class
│   │   │       │   ├── db.cfg
│   │   │       │   └── META-INF
│   │   │       │       └── persistence.xml
│   │   │       ├── faces-config.xml
│   │   │       ├── lib
│   │   │       │   ├── checker-qual-3.31.0.jar
│   │   │       │   ├── jakarta.persistence-api-3.0.0.jar
│   │   │       │   ├── logback-classic-1.2.9.jar
│   │   │       │   ├── logback-core-1.2.9.jar
│   │   │       │   ├── org.eclipse.persistence.asm-9.1.0.jar
│   │   │       │   ├── org.eclipse.persistence.core-3.0.2.jar
│   │   │       │   ├── org.eclipse.persistence.jpa-3.0.2.jar
│   │   │       │   ├── org.eclipse.persistence.jpa.jpql-3.0.2.jar
│   │   │       │   ├── postgresql-42.6.0.jar
│   │   │       │   ├── primefaces-12.0.0.jar
│   │   │       │   └── slf4j-api-1.7.32.jar
│   │   │       └── web.xml
│   │   ├── interactive-graph-ui-1.0-SNAPSHOT.war
│   │   ├── maven-archiver
│   │   │   └── pom.properties
│   │   └── maven-status
│   │       └── maven-compiler-plugin
│   │           └── compile
│   │               └── default-compile
│   │                   ├── createdFiles.lst
│   │                   └── inputFiles.lst
│   ├── tree.md
│   └── yarn.lock
├── tree.md
└── var.md

80 directories, 196 files
