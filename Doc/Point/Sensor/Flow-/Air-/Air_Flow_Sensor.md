[Index](../../../../index.md) > [Point](../../../Point.md) > [Sensor](../../Sensor.md) > [Flow_Sensor](../Flow_Sensor.md) > [Air_Flow_Sensor](#)
# Air_Flow_Sensor

Measures the rate of flow of air


**Display name:** Air Flow Sensor<br />
**DTMI:** dtmi:org:brickschema:schema:Brick:Air_Flow_Sensor;1

---

## Child interfaces
* [Bypass_Air_Flow_Sensor](Bypass-.md)
* [Discharge_Air_Flow_Sensor](Discharge-/Discharge_Air_Flow_Sensor.md)
* [Exhaust_Air_Flow_Sensor](Exhaust-/Exhaust_Air_Flow_Sensor.md)
* [Fume_Hood_Air_Flow_Sensor](Fume_Hood-.md)
* [Mixed_Air_Flow_Sensor](Mixed-.md)
* [Outside_Air_Flow_Sensor](Outside-.md)
* [Return_Air_Flow_Sensor](Return-.md)
* [Supply_Air_Flow_Sensor](Supply-/Supply_Air_Flow_Sensor.md)

---

## Relationships

### Inherited Relationships
* **[Point](../../../Point.md):** isPointOf

---

## Properties

### Inherited Properties
* **[Flow_Sensor](../Flow_Sensor.md):** lastKnownValue
* **[Point](../../../Point.md):** aggregate, customTags, externalIds, hasQuantity, hasSubstance, name

---

## Target Of
### General
* [Point](../../../Point.md).isPointOf
* [Agent](../../../../Agent/Agent.md).owns
* [Space](../../../../Space/Space.md).isLocationOf
* [Equipment](../../../../Asset/Equipment/Equipment.md).feeds
* [Equipment](../../../../Asset/Equipment/Equipment.md).isFedBy
* [Architecture](../../../../Space/Architecture/Architecture.md).isFedBy
* [Document](../../../../Information/Document/Document.md).documentTopic
* [Document](../../../../Information/Document/Document.md).url
* [EquipmentCollection](../../../../Collection/Equipment-.md).feeds
* [Lease](../../../../Event/Lease.md).leaseOf
* [PointOfInterest](../../../../Information/PointOfInterest.md).objectOfInterest
* [Portfolio](../../../../Collection/Portfolio.md).includes
* [ServiceObject](../../../../Information/ServiceObject/ServiceObject.md).relatedTo
* [Meter](../../../../Asset/Equipment/Meter/Meter.md).meters
### Inherited
* [ActuationEvent](../../../../Event/Point-/ActuationEvent.md).targetPoint
* [Architecture](../../../../Space/Architecture/Architecture.md).hasPoint
* [Asset](../../../../Asset/Asset.md).hasPoint
* [EquipmentCollection](../../../../Collection/Equipment-.md).hasPoint
* [ExceptionEvent](../../../../Event/Point-/ExceptionEvent.md).sourcePoint
* [ObservationEvent](../../../../Event/Point-/ObservationEvent.md).sourcePoint
* [ServiceObject](../../../../Information/ServiceObject/ServiceObject.md).producedBy