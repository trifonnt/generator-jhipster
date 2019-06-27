This project is FRIENDLY fork of the awesome JHipster project.

PLEASE USE it on your risk and only if you know what you are doing!

List of new features added to JHipster:

[x] Fluent methods for User class.

[x] Generate methods ENTITY getBy<UNIQUE_FIELD>(...) in Java service classes.

[x] Generate methods ENTITY getOrCreateBy<UNIQUE_FIELD>(...) in Java service classes.

[x] Generate method to delete multiple records by ids in Java REST Resource classes.

[x] Generate REST endpoint /api/ENTITY/template which returns template for new record creation.

[x] Generate Builder class for each ENTITY.

[x] Save File name for byte[] field types.

[x] Save File size for byte[] field types.

[x] When byte[] field is updated and set to null then set xxxContentType, xxxFieldName and xxxFieldSize to null.
    - /generator-jhipster-x/generators/entity-server/templates/src/main/java/package/common/nullify-file-name_template.ejs

[x] Added PATCH method to jhipster spring-controller.

[x] Improved i18n .json files to have plural names for one-to-many and many-to-many relationships.

[x] Added importBy<UNIQUE_FIELD>(...) in Java service classes.

[x] Added new model field "defaultValueConstant" to .jhipster/MODEL.json

[x] Generate REST endpoint /api/ENTITY/{id}/RELATIONSHIP_NAME/template

[x] Implemented PATCH method. Added new REST endpoint /api/ENTITY/{id}

[x] Added HTML5 mode. https://www.jhipster.tech/tips/010_tip_configuring_html_5_mode.html

[] Different DB Sequence for each entity.
