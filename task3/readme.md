# Description

Модуль Management библиотеки Storeon позволяет управлять состоянием виджета при помощи определенного набора событий.

# Events

## @init
Событие инициализирует состояние виджета дефолтными значениями из файла конфигурации [src/configs/uiManagment.ts](https://github.com/sovaai/chatKit-lib/blob/master/src/configs/uiManagment.ts)

## openChat
Событие изменяет параметр виджета `common.chatIsOpen`. Тип значений, записываемых в параметр: `boolean`.

## showMsgLoad
Событие изменяет параметр виджета `common.showMsgLoad`. Тип значений, записываемых в параметр: `boolean`.

## showNotification
Событие изменяет параметр виджета `common.showNotification`. Тип значений, записываемых в параметр: `boolean`.

## setUpCommon
Событие конфигурирует общие параметры виджета.

## showRate
Событие изменяет параметр виджета `common.showRate`. Тип значений, записываемых в параметр: `boolean`.

## blockSender
Событие изменяет параметр компонента `components.Sender.blockInput`. Тип значений, записываемых в параметр: `boolean`.

## setUpComponent
Событие конфигурирует выбранный компонент.

## changeSenderFocusInf
Событие изменяет параметр компонента `components.Sender.inFocus` на противоположный. Тип значений, записываемых в параметр: `boolean`.

## showSettings
Событие изменяет параметр виджета `common.showSettings` на противоположный. Тип значений, записываемых в параметр: `boolean`.

## toggleDisplayMessageTime
Событие изменяет параметр компонента `components.Message.showDate` на противоположный. Тип значений, записываемых в параметр: `boolean`.

## toggleSearchActiveStatus
Событие изменяет параметр компонента `components.Header.search.active` на противоположный. Тип значений, записываемых в параметр: `boolean`.

## changeSearchValue
Событие изменяет параметр компонента `components.Header.search.searchValue`. Тип значений, записываемых в параметр: `string`.

## changeFoundGroup
Событие изменяет параметр компонента `components.Header.search.found`. Тип значений, записываемых в параметр: `string`. При эмиттинге события указывается одно из действий: `clear`, `add`, `delete`.

## scrollToFoundMessage
Событие изменяет параметр компонента `components.Header.search.foundMessage`. Тип значений, записываемых в параметр: `number`.

## showDropZone
Событие изменяет параметр компонента `components.Sender.showDropZone`. Тип значений, записываемых в параметр: `boolean`.
