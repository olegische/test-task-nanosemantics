# Description

Модуль Management библиотеки Storeon позволяет управлять состоянием виджета при помощи определенного набора событий. При реализации виджета, производится эмиттиг события с указанием соответствующих событию.

# Events

## @init
Событие инициализирует состояние виджета дефолтными значениями из файла конфигурации [src/configs/uiManagment.ts](https://github.com/sovaai/chatKit-lib/blob/master/src/configs/uiManagment.ts)

## openChat
Событие изменяет параметр виджета `common.chatIsOpen`

### Parameters
`status`, тип значений `boolean`

## showMsgLoad
Событие изменяет параметр виджета `common.showMsgLoad`

### Parameters
`status`, тип значений `boolean`

## showNotification
Событие изменяет параметр виджета `common.showNotification`

### Parameters
`status`, тип значений `boolean`

## setUpCommon
Событие конфигурирует общие параметры виджета.

### Parameters
`data`, структура данных, соответствующая структуре стейта

## showRate
Событие изменяет параметр виджета `common.showRate`

### Parameters
`status`, тип значений `boolean`

## blockSender
Событие изменяет параметр компонента `components.Sender.blockInput`

### Parameters
`status`, тип значений `boolean`

## setUpComponent
Событие конфигурирует выбранный компонент.

### Parameters
`componentName`, тип значений `string`  
`data`, структура данных, соответствующая структуре стейта

## changeSenderFocusInf
Событие изменяет параметр компонента `components.Sender.inFocus` на противоположный

## showSettings
Событие изменяет параметр виджета `common.showSettings` на противоположный

## toggleDisplayMessageTime
Событие изменяет параметр компонента `components.Message.showDate` на противоположный

## toggleSearchActiveStatus
Событие изменяет параметр компонента `components.Header.search.active` на противоположный

## changeSearchValue
Событие изменяет параметр компонента `components.Header.search.searchValue`

### Parameters
`searchValue`, тип значений `string`

## changeFoundGroup
Событие изменяет параметр компонента `components.Header.search.found`. Тип значений, записываемых в параметр: `string`. При эмиттинге события указывается одно из действий: `clear`, `add`, `delete`.

### Parameters
`messageId`, идентификатор сообщения  
`action`, одно из действий: `clear`, `add`, `delete`

## scrollToFoundMessage
Событие изменяет параметр компонента `components.Header.search.foundMessage`. Тип значений, записываемых в параметр: `number`.

### Parameters
`messageNumber`, тип значений `number`

## showDropZone
Событие изменяет параметр компонента `components.Sender.showDropZone`. Тип значений, записываемых в параметр: `boolean`.

### Parameters
`status`, тип значений `boolean`
