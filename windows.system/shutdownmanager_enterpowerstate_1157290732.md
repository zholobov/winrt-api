---
-api-id: M:Windows.System.ShutdownManager.EnterPowerState(Windows.System.PowerState,Windows.Foundation.TimeSpan)
-api-type: winrt method
---

<!-- Method syntax.
public void ShutdownManager.EnterPowerState(PowerState powerState, TimeSpan wakeUpAfter)
-->

# Windows.System.ShutdownManager.EnterPowerState

## -description
Instructs a fixed-purpose device to enter the given power state, then wake up after the given period of time.

## -parameters

### -param powerState

The power state to enter. 

### -param wakeUpAfter

The amount of time to wake up after.

## -remarks

This API requires the use of the IoT **systemManagement** capability, and the inclusion of **iot** in the **IgnorableNamespaces** list. Users can add the following to their **Package.appmanifest**:`
<iot:Capability Name="systemManagement"/>`, and add **iot** to their existing list of **IgnorableNamespaces**.

## -see-also

## -examples

