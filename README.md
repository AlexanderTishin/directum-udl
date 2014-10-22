directum-udl
============

Universal Directum Library версия от 22.10.2014


Platforms
=========

DIRECTUM 5.0.*


Installation
============

1.	Открыть утилиту "Импорт разработки" в компоненте "Утилиты разработчика";
2.	В появившемся окне указать путь к пакету разработки \Universal Directum Library\import.isx, нажать "Открыть";
3.	После окончания сравнения разработки при необходимости проверить или изменить состав принимаемыех элементов по столбцам 
    "Принять" и "Тип модификации";
4.	Нажать кнопку "Импортировать";
5.	В окне "Параметры импорта" установить галочку "Генерировать реквизиты" (рекомендуется) и "Принимать настройки видов 
    справочников"; 
6.	Остальные параметры устанавливаются при необходимости; 
7.	Нажать OK. Дождаться завершения импорта разработки.


Contents
========

Перечень функций по группам:
  Интеграция систем
    UDL_GetDirectumObjectID
    UDL_GetIntegratedSystemObjectID
    UDL_GetIntegratedSystemObjectKeyFields
  Канцелярия
    UDL_CreateRRC
    UDL_GetRRCListOnEDoc
  Прочие функции
    UDL_CheckINN
    UDL_CreateWEBAccessHyperlink
    UDL_GetProgressText
    UDL_GiveAccessToSQLTable
    UDL_OpenURL
    UDL_SetDataToClipboard
    UDL_SetupOurFirmConstants
    UDL_URLEncode
  Работа с документами
    UDL_GetEDocVersionCreateDate
  Работа с задачами и заданиями
    UDL_AbortTaskByID
    UDL_GetTaskHierarchy
    UDL_PerformJobByID
  Работа с отчетами
    UDL_ReportExecute
  Работа с пользователями и работниками
    UDL_CreateUser
    UDL_GetAllHeadOfDepartments
    UDL_GetCurrentUser
    UDL_GetGroupMembers
    UDL_GetSingleEmployeeByUserID
    UDL_UserIsGroupMember
  Работа с типовыми маршрутами и ролями
    UDL_CalculateRoleByAnotherRole
    UDL_CalculateRoleByConstant
    UDL_CalculateRoleByDepartmentHierarchy
    UDL_CalculateRoleByEmployeeParam
    UDL_CalculateRoleByRefEDocParam
    UDL_ClearTaskParam
    UDL_FindValueInTaskParamCollection
    UDL_GetRoleMembers
    UDL_SetTaskParamByAnotherTaskParam
    UDL_WFBlockApplySpecialRights
    UDL_WFBlockLifeCycleStageChanging
    UDL_WFBlockRefStageChanging
    UDL_WFBlockRevokeSpecialRights
  Работа с файлами
    UDL_GetLogFile
  Работа со справочниками и ТКЭД
    UDL_AttachedToTaskSearch
    UDL_BoundDocumentSearch
    UDL_CheckRecordUniqueness
    UDL_CheckRequiredRequisite
    UDL_CopyRequisiteValue
    UDL_GetAddSelectForEDocName
    UDL_GetAddWhereForFilterByBoundDocs
    UDL_GetAddWhereForFilterByConstUserGroup
    UDL_GetAddWhereForFilterByConstUserGroupDetail
    UDL_GetAddWhereForFilterByDepartmentEmployee
    UDL_GetAddWhereForFilterByDepartmentEmployeeDetail
    UDL_GetAddWhereForFilterByEmployee
    UDL_GetAddWhereForFilterByEmployeeDetail
    UDL_GetAddWhereForFilterByHierarchyDepartmentEmployee
    UDL_GetAddWhereForFilterByHierarchyDepartmentEmployeeDetail
    UDL_GetAddWhereForFilterByLeadOurFirm
    UDL_GetAddWhereForFilterByLeadOurFirmDetail
    UDL_GetAddWhereForFilterByOurFirm
    UDL_GetAddWhereForFilterByOurFirmDetail
    UDL_GetLeaderReferenceName
    UDL_GetMaxNumber
    UDL_GetRecordFamily
    UDL_GetRecordFamilyByCode
    UDL_GetSubordinateRecords
    UDL_SelectAutomatedEmployees
    UDL_SelectHeadOfOurFirms
    UDL_SetAvailabilityActions
    UDL_SetAvailabilityControls
    UDL_SetAvailabilityReferenceActions
    UDL_SetAvailabilityRequisites
    UDL_SetRequisiteValueWithDisabledEvents
    UDL_ShowEDocument
    UDL_ShowLinkedReference
    UDL_ShowReferenceCard
    UDL_UserHasPrivilegesViewAllRecords
    UDL_WebBrowserControlNavigate
