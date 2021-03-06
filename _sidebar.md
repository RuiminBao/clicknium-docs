- **Clicknium Document**
  - [Getting started](./doc/gettingstart.md)
  - Develop tools
    - [Clicknium VSCode Extension](./doc/developtools/vscode.md)
    - [Automation Extensions](./doc/developtools/extensions/extensions.md)
      - [Chrome Extension](./doc/developtools/extensions/chromeextension.md)
      - [Edge Extension](./doc/developtools/extensions/edgeextension.md)
      - [FireFox Extension](./doc/developtools/extensions/firefoxextension.md)
      - [Java Extension](./doc/developtools/extensions/javaextension.md)
  - [Automation](./doc/automation/automation.md)
    - [Image Automation](./doc/automation/image.md)
    - [UiElement Property](./doc/automation/property.md)
    - [Locator](./doc/automation/locator.md)
    - [Parametric Locator](./doc/automation/parametric_locator.md)
    - [SAP Automation](./doc/automation/sap.md)
  - [Cloud Product](./doc/products.md)
  - [Clicknium Python SDK](./doc/api/python/pythonsdk.md)
    - [General Functions](./doc/api/python/globalfunctions.md)
      - [clicknium.find_element](./doc/api/python/find_element.md)
      - [clicknium.is_exist](./doc/api/python/is_exist.md)      
      - [clicknium.wait_appear](./doc/api/python/wait_appear.md)
      - [clicknium.wait_disappear](./doc/api/python/wait_disappear.md)
      - [clicknium.wait_property](./doc/api/python/wait_property.md)
      - [clicknium.send_hotkey](./doc/api/python/send_hotkey.md)
    - [UiElement](./doc/api/python/uielement/uielement.md)
      - [click](./doc/api/python/uielement/click.md)
      - [double_click](./doc/api/python/uielement/double_click.md)
      - [drag_drop](./doc/api/python/uielement/drag_drop.md)
      - [get_position](./doc/api/python/uielement/get_position.md)
      - [get_property](./doc/api/python/uielement/get_property.md)
      - [get_size](./doc/api/python/uielement/get_size.md)
      - [set_text](./doc/api/python/uielement/set_text.md)
      - [get_text](./doc/api/python/uielement/get_text.md)
      - [clear_text](./doc/api/python/uielement/clear_text.md)
      - [highlight](./doc/api/python/uielement/highlight.md)
      - [hover](./doc/api/python/uielement/hover.md)
      - [save_to_image](./doc/api/python/uielement/save_to_image.md)
      - [select_item](./doc/api/python/uielement/select_item.md)
      - [select_items](./doc/api/python/uielement/select_items.md)
      - [send_hotkey](./doc/api/python/uielement/send_hotkey.md)
      - [set_checkbox](./doc/api/python/uielement/set_checkbox.md)
      - [set_focus](./doc/api/python/uielement/set_focus.md)      
    - [WebDriver](./doc/api/python/webdriver/webdriver.md)
      - [open](./doc/api/python/webdriver/open.md)
      - [attach](./doc/api/python/webdriver/attach.md)
      - [Browser](./doc/api/python/webdriver/browser/browser.md)
        - [find_element](./doc/api/python/webdriver/browser/find_element.md)
        - [is_exist](./doc/api/python/webdriver/browser/is_exist.md)
        - [wait_appear](./doc/api/python/webdriver/browser/wait_appear.md)
        - [wait_disappear](./doc/api/python/webdriver/browser/wait_disappear.md)
        - [wait_property](./doc/api/python/webdriver/browser/wait_property.md)
        - [set_property](./doc/api/python/webdriver/browser/set_property.md)
        - [close_tab](./doc/api/python/webdriver/browser/close_tab.md)
        - [close](./doc/api/python/webdriver/browser/close.md)
        - [navigate](./doc/api/python/webdriver/browser/navigate.md)
        - [refresh](./doc/api/python/webdriver/browser/refresh.md)        
      - [WebExtension](./doc/api/python/webdriver/webextension/webextension.md)
        - [install](./doc/api/python/webdriver/webextension/install.md)
        - [update](./doc/api/python/webdriver/webextension/update.md)
    - [Desktop](./doc/api/python/desktop/desktop.md)
      - [maximize](./doc/api/python/desktop/maximize.md)
      - [minimize](./doc/api/python/desktop/minimize.md)
      - [restore](./doc/api/python/desktop/restore.md)
    - [Sap](./doc/api/python/sap/sap.md)
      - [login](./doc/api/python/sap/login.md)
      - [select_item](./doc/api/python/sap/select_item.md)
      - [call_transaction](./doc/api/python/sap/call_transaction.md)
      - [get_statusbar](./doc/api/python/sap/get_statusbar.md)      
    - [Java](./doc/api/python/java/java.md)
      - [install](./doc/api/python/java/install.md)
      - [uninstall](./doc/api/python/java/uninstall.md)
    - [Exceptions](./doc/api/python/exceptions/exceptions.md)
      - [BaseError](./doc/api/python/exceptions/baseerror.md)
      - [ArgumentError](./doc/api/python/exceptions/argumenterror.md)
      - [ArgumentNullError](./doc/api/python/exceptions/argumentnullerror.md)
      - [ArgumentOutOfRangeError](./doc/api/python/exceptions/argumentoutofrangeerror.md)      
      - [LocatorUndefinedError](./doc/api/python/exceptions/locatorundefinederror.md)
      - [TimeoutOperationError](./doc/api/python/exceptions/timeoutoperationerror.md)
      - [ElementCanNotFoundError](./doc/api/python/exceptions/elementcannotfounderror.md)
      - [ExtensionOperationError](./doc/api/python/exceptions/extensionoperationerror.md)
      - [NotSupportedError](./doc/api/python/exceptions/notsupportederror.md)
      - [NotSupportedOperationError](./doc/api/python/exceptions/notsupportedoperationerror.md)
      - [NotSupportedOperationOptionError](./doc/api/python/exceptions/notsupportedoperationoptionerror)
      - [InvalidOperationError](./doc/api/python/exceptions/invalidoperationerror.md)
      - [InvalidSelectedItemError](./doc/api/python/exceptions/invalidselecteditemerror.md)      
      - [DesktopError](./doc/api/python/exceptions/desktoperror.md)
      - [WindowsNativeError](./doc/api/python/exceptions/windowsnativeerror.md)
      - [UiaPatternNotFoundError](./doc/api/python/exceptions/uiapatternnotfounderror.md)
      - [ScreenOperationError](./doc/api/python/exceptions/screenoperationerror.md)
      - [WebError](./doc/api/python/exceptions/weberror.md)
      - [BrowserNotRunError](./doc/api/python/exceptions/browsernotrunerror.md)
      - [BrowserNotInstallError](./doc/api/python/exceptions/browsernotinstallerror.md)
      - [UnreachableBrowserExtensionError](./doc/api/python/exceptions/unreachablebrowserextensionerror.md)
      - [WebElementNotRespondingError](./doc/api/python/exceptions/webelementnotrespondingerror.md)
  - [Sample automation cases](./doc/cases.md)
- [**Contact us**](./doc/contact/contact.md)
