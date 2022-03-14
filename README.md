package generated;

import javax.xml.bind.annotation.XmlAccessType;
import javax.xml.bind.annotation.XmlAccessorType;
import javax.xml.bind.annotation.XmlElement;
import javax.xml.bind.annotation.XmlRootElement;
import javax.xml.bind.annotation.XmlType;

@XmlAccessorType(XmlAccessType.FIELD)
@XmlType(name = "", propOrder = { "body", "docId", "meta", "relationships", "rules", "type" })
@XmlRootElement(name = "root")
public class Root {

	@XmlElement(required = true)
	protected Root.Body body;
	@XmlElement(required = true)
	protected String docId;
	@XmlElement(required = true)
	protected Root.Meta meta;
	@XmlElement(required = true)
	protected Root.Relationships relationships;
	@XmlElement(required = true)
	protected Root.Rules rules;
	@XmlElement(required = true)
	protected String type;

	public Root.Body getBody() {
		return body;
	}

	public void setBody(Root.Body value) {
		this.body = value;
	}

	public String getDocId() {
		return docId;
	}

	public void setDocId(String value) {
		this.docId = value;
	}

	public Root.Meta getMeta() {
		return meta;
	}

	public void setMeta(Root.Meta value) {
		this.meta = value;
	}

	public Root.Relationships getRelationships() {
		return relationships;
	}

	public void setRelationships(Root.Relationships value) {
		this.relationships = value;
	}

	public Root.Rules getRules() {
		return rules;
	}

	public void setRules(Root.Rules value) {
		this.rules = value;
	}

	public String getType() {
		return type;
	}

	public void setType(String value) {
		this.type = value;
	}

	@XmlAccessorType(XmlAccessType.FIELD)
	@XmlType(name = "", propOrder = { "deviceLongitude", "status", "deviceLatitude" })
	public static class Body {

		protected float deviceLongitude;
		@XmlElement(required = true)
		protected String status;
		protected float deviceLatitude;

		public float getDeviceLongitude() {
			return deviceLongitude;
		}

		public void setDeviceLongitude(float value) {
			this.deviceLongitude = value;
		}

		public String getStatus() {
			return status;
		}

		public void setStatus(String value) {
			this.status = value;
		}

		public float getDeviceLatitude() {
			return deviceLatitude;
		}

		public void setDeviceLatitude(float value) {
			this.deviceLatitude = value;
		}

	}

	@XmlAccessorType(XmlAccessType.FIELD)
	@XmlType(name = "", propOrder = { "appId", "createdAt", "version", "contextId", "updatedAt" })
	public static class Meta {

		@XmlElement(required = true)
		protected String appId;
		@XmlElement(required = true)
		protected String createdAt;
		protected byte version;
		@XmlElement(required = true)
		protected String contextId;
		@XmlElement(required = true)
		protected String updatedAt;

		public String getAppId() {
			return appId;
		}

		public void setAppId(String value) {
			this.appId = value;
		}

		public String getCreatedAt() {
			return createdAt;
		}

		public void setCreatedAt(String value) {
			this.createdAt = value;
		}

		public byte getVersion() {
			return version;
		}

		public void setVersion(byte value) {
			this.version = value;
		}

		public String getContextId() {
			return contextId;
		}

		public void setContextId(String value) {
			this.contextId = value;
		}

		public String getUpdatedAt() {
			return updatedAt;
		}

		public void setUpdatedAt(String value) {
			this.updatedAt = value;
		}

	}

	@XmlAccessorType(XmlAccessType.FIELD)
	@XmlType(name = "", propOrder = { "deviceSerial", "driverId", "driverExternalId", "stopId", "workAssignmentId" })
	public static class Relationships {

		@XmlElement(required = true)
		protected String deviceSerial;
		protected long driverId;
		protected int driverExternalId;
		@XmlElement(required = true)
		protected String stopId;
		@XmlElement(required = true)
		protected String workAssignmentId;

		public String getDeviceSerial() {
			return deviceSerial;
		}

		public void setDeviceSerial(String value) {
			this.deviceSerial = value;
		}

		public long getDriverId() {
			return driverId;
		}

		public void setDriverId(long value) {
			this.driverId = value;
		}

		public int getDriverExternalId() {
			return driverExternalId;
		}

		public void setDriverExternalId(int value) {
			this.driverExternalId = value;
		}

		public String getStopId() {
			return stopId;
		}

		public void setStopId(String value) {
			this.stopId = value;
		}

		public String getWorkAssignmentId() {
			return workAssignmentId;
		}

		public void setWorkAssignmentId(String value) {
			this.workAssignmentId = value;
		}

	}

	@XmlAccessorType(XmlAccessType.FIELD)
	@XmlType(name = "", propOrder = { "topic", "source", "targets" })
	public static class Rules {

		@XmlElement(required = true)
		protected String topic;
		@XmlElement(required = true)
		protected String source;
		@XmlElement(required = true)
		protected String targets;

		public String getTopic() {
			return topic;
		}

		public void setTopic(String value) {
			this.topic = value;
		}

		public String getSource() {
			return source;
		}

		public void setSource(String value) {
			this.source = value;
		}

		public String getTargets() {
			return targets;
		}

		public void setTargets(String value) {
			this.targets = value;
		}

	}

}
