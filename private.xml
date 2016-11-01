<?xml version="1.0"?>
<root>
    <!-- XCode 정의 -->
    <appdef>
        <appname>XCODE</appname>
        <equal>com.apple.dt.Xcode</equal>
    </appdef>
    
    <item>
        <name>SEGUNLEE Custom(M545)</name>
        
        <!--  디바이스 정의 (M545) -->
        <devicevendordef>
            <vendorname>LOGITECH</vendorname>
            <vendorid>0x046d</vendorid>
        </devicevendordef>
        <deviceproductdef>
            <productname>USB_Receiver</productname>
            <productid>0xc52b</productid>
        </deviceproductdef>
        
        <!-- Items -->
        <item>
            <name>Use Button4/Button5 to XCode File Navigation</name>
            <identifier>private.back_forward_with_exceptions</identifier>
            <device_only>DeviceVendor::LOGITECH, DeviceProduct::USB_Receiver</device_only>
            <block>
                <autogen>__PointingButtonToKey__ PointingButton::BUTTON4,
                    KeyCode::BRACKET_LEFT, ModifierFlag::COMMAND_L</autogen>
                <autogen>__PointingButtonToKey__ PointingButton::BUTTON5,
                    KeyCode::BRACKET_RIGHT, ModifierFlag::COMMAND_L</autogen>
                <not>XCODE</not>
            </block>
            <block>
                <autogen>__PointingButtonToKey__ PointingButton::BUTTON4,
                    KeyCode::CURSOR_LEFT, ModifierFlag::COMMAND_L | ModifierFlag::CONTROL_L</autogen>
                <autogen>__PointingButtonToKey__ PointingButton::BUTTON5,
                    KeyCode::CURSOR_RIGHT, ModifierFlag::COMMAND_L | ModifierFlag::CONTROL_L</autogen>
                <only>XCODE</only>
            </block>
            <block>
                <autogen>__PointingButtonToKey__ PointingButton::BUTTON4,
                    KeyCode::CURSOR_LEFT, ModifierFlag::OPTION_L</autogen>
                <autogen>__PointingButtonToKey__ PointingButton::BUTTON5,
                    KeyCode::CURSOR_RIGHT, ModifierFlag::OPTION_L</autogen>
            </block>
        </item>

        <item>
            <name>Use Side Buttons to Browser Navigation</name>
            <identifier>private.side_buttons_to_browser_navigation</identifier>
            <device_only>DeviceVendor::LOGITECH, DeviceProduct::USB_Receiver</device_only>
            <autogen>
                __SimultaneousKeyPresses__
                KeyCode :: COMMAND_L, KeyCode :: D,
                KeyCode :: BRACKET_LEFT, ModifierFlag :: COMMAND_L
            </autogen>
            <autogen>
                __KeyToKey__
                KeyCode :: COMMAND_L,
                KeyCode :: BRACKET_RIGHT, ModifierFlag :: COMMAND_L
            </autogen>
        </item>

    </item>
</root>
