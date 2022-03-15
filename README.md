
package generated;

import javax.xml.bind.annotation.XmlAccessType;
import javax.xml.bind.annotation.XmlAccessorType;
import javax.xml.bind.annotation.XmlAttribute;
import javax.xml.bind.annotation.XmlElement;
import javax.xml.bind.annotation.XmlRootElement;
import javax.xml.bind.annotation.XmlType;
import javax.xml.bind.annotation.XmlValue;



@XmlAccessorType(XmlAccessType.FIELD)
@XmlType(name = "", propOrder = {
    "element"
})
@XmlRootElement(name = "root")
public class Root {

    @XmlElement(required = true)
    protected Root.Element element;

    /**
     * Gets the value of the element property.
     * 
     * @return
     *     possible object is
     *     {@link Root.Element }
     *     
     */
    public Root.Element getElement() {
        return element;
    }

    /**
     * Sets the value of the element property.
     * 
     * @param value
     *     allowed object is
     *     {@link Root.Element }
     *     
     */
    public void setElement(Root.Element value) {
        this.element = value;
    }


    /**
     * <p>Java class for anonymous complex type.
     * 
     * <p>The following schema fragment specifies the expected content contained within this class.
     * 
     * <pre>
     * &lt;complexType>
     *   &lt;complexContent>
     *     &lt;restriction base="{http://www.w3.org/2001/XMLSchema}anyType">
     *       &lt;sequence>
     *         &lt;element name="key" type="{http://www.w3.org/2001/XMLSchema}string"/>
     *         &lt;element name="value">
     *           &lt;complexType>
     *             &lt;complexContent>
     *               &lt;restriction base="{http://www.w3.org/2001/XMLSchema}anyType">
     *                 &lt;sequence>
     *                   &lt;element name="body">
     *                     &lt;complexType>
     *                       &lt;complexContent>
     *                         &lt;restriction base="{http://www.w3.org/2001/XMLSchema}anyType">
     *                           &lt;sequence>
     *                             &lt;element name="deviceLatitude" type="{http://www.w3.org/2001/XMLSchema}float"/>
     *                             &lt;element name="deviceLongitude" type="{http://www.w3.org/2001/XMLSchema}float"/>
     *                             &lt;element name="status" type="{http://www.w3.org/2001/XMLSchema}string"/>
     *                           &lt;/sequence>
     *                         &lt;/restriction>
     *                       &lt;/complexContent>
     *                     &lt;/complexType>
     *                   &lt;/element>
     *                   &lt;element name="docId" type="{http://www.w3.org/2001/XMLSchema}string"/>
     *                   &lt;element name="meta">
     *                     &lt;complexType>
     *                       &lt;complexContent>
     *                         &lt;restriction base="{http://www.w3.org/2001/XMLSchema}anyType">
     *                           &lt;sequence>
     *                             &lt;element name="appId" type="{http://www.w3.org/2001/XMLSchema}string"/>
     *                             &lt;element name="contextId">
     *                               &lt;complexType>
     *                                 &lt;simpleContent>
     *                                   &lt;extension base="&lt;http://www.w3.org/2001/XMLSchema>string">
     *                                     &lt;attribute name="null" type="{http://www.w3.org/2001/XMLSchema}string" />
     *                                   &lt;/extension>
     *                                 &lt;/simpleContent>
     *                               &lt;/complexType>
     *                             &lt;/element>
     *                             &lt;element name="createdAt" type="{http://www.w3.org/2001/XMLSchema}string"/>
     *                             &lt;element name="updatedAt" type="{http://www.w3.org/2001/XMLSchema}string"/>
     *                             &lt;element name="version" type="{http://www.w3.org/2001/XMLSchema}byte"/>
     *                           &lt;/sequence>
     *                         &lt;/restriction>
     *                       &lt;/complexContent>
     *                     &lt;/complexType>
     *                   &lt;/element>
     *                   &lt;element name="relationships">
     *                     &lt;complexType>
     *                       &lt;complexContent>
     *                         &lt;restriction base="{http://www.w3.org/2001/XMLSchema}anyType">
     *                           &lt;sequence>
     *                             &lt;element name="deviceSerial" type="{http://www.w3.org/2001/XMLSchema}string"/>
     *                             &lt;element name="driverExternalId" type="{http://www.w3.org/2001/XMLSchema}int"/>
     *                             &lt;element name="driverId" type="{http://www.w3.org/2001/XMLSchema}long"/>
     *                             &lt;element name="stopId" type="{http://www.w3.org/2001/XMLSchema}string"/>
     *                             &lt;element name="workAssignmentId" type="{http://www.w3.org/2001/XMLSchema}string"/>
     *                           &lt;/sequence>
     *                         &lt;/restriction>
     *                       &lt;/complexContent>
     *                     &lt;/complexType>
     *                   &lt;/element>
     *                   &lt;element name="rules">
     *                     &lt;complexType>
     *                       &lt;complexContent>
     *                         &lt;restriction base="{http://www.w3.org/2001/XMLSchema}anyType">
     *                           &lt;sequence>
     *                             &lt;element name="source" type="{http://www.w3.org/2001/XMLSchema}string"/>
     *                             &lt;element name="targets">
     *                               &lt;complexType>
     *                                 &lt;complexContent>
     *                                   &lt;restriction base="{http://www.w3.org/2001/XMLSchema}anyType">
     *                                     &lt;sequence>
     *                                       &lt;element name="element" type="{http://www.w3.org/2001/XMLSchema}string"/>
     *                                     &lt;/sequence>
     *                                   &lt;/restriction>
     *                                 &lt;/complexContent>
     *                               &lt;/complexType>
     *                             &lt;/element>
     *                             &lt;element name="topic" type="{http://www.w3.org/2001/XMLSchema}string"/>
     *                           &lt;/sequence>
     *                         &lt;/restriction>
     *                       &lt;/complexContent>
     *                     &lt;/complexType>
     *                   &lt;/element>
     *                   &lt;element name="type" type="{http://www.w3.org/2001/XMLSchema}string"/>
     *                 &lt;/sequence>
     *               &lt;/restriction>
     *             &lt;/complexContent>
     *           &lt;/complexType>
     *         &lt;/element>
     *       &lt;/sequence>
     *     &lt;/restriction>
     *   &lt;/complexContent>
     * &lt;/complexType>
     * </pre>
     * 
     * 
     */
    @XmlAccessorType(XmlAccessType.FIELD)
    @XmlType(name = "", propOrder = {
        "key",
        "value"
    })
    public static class Element {

        @XmlElement(required = true)
        protected String key;
        @XmlElement(required = true)
        protected Root.Element.Value value;

        /**
         * Gets the value of the key property.
         * 
         * @return
         *     possible object is
         *     {@link String }
         *     
         */
        public String getKey() {
            return key;
        }

        /**
         * Sets the value of the key property.
         * 
         * @param value
         *     allowed object is
         *     {@link String }
         *     
         */
        public void setKey(String value) {
            this.key = value;
        }

        /**
         * Gets the value of the value property.
         * 
         * @return
         *     possible object is
         *     {@link Root.Element.Value }
         *     
         */
        public Root.Element.Value getValue() {
            return value;
        }

        /**
         * Sets the value of the value property.
         * 
         * @param value
         *     allowed object is
         *     {@link Root.Element.Value }
         *     
         */
        public void setValue(Root.Element.Value value) {
            this.value = value;
        }


        /**
         * <p>Java class for anonymous complex type.
         * 
         * <p>The following schema fragment specifies the expected content contained within this class.
         * 
         * <pre>
         * &lt;complexType>
         *   &lt;complexContent>
         *     &lt;restriction base="{http://www.w3.org/2001/XMLSchema}anyType">
         *       &lt;sequence>
         *         &lt;element name="body">
         *           &lt;complexType>
         *             &lt;complexContent>
         *               &lt;restriction base="{http://www.w3.org/2001/XMLSchema}anyType">
         *                 &lt;sequence>
         *                   &lt;element name="deviceLatitude" type="{http://www.w3.org/2001/XMLSchema}float"/>
         *                   &lt;element name="deviceLongitude" type="{http://www.w3.org/2001/XMLSchema}float"/>
         *                   &lt;element name="status" type="{http://www.w3.org/2001/XMLSchema}string"/>
         *                 &lt;/sequence>
         *               &lt;/restriction>
         *             &lt;/complexContent>
         *           &lt;/complexType>
         *         &lt;/element>
         *         &lt;element name="docId" type="{http://www.w3.org/2001/XMLSchema}string"/>
         *         &lt;element name="meta">
         *           &lt;complexType>
         *             &lt;complexContent>
         *               &lt;restriction base="{http://www.w3.org/2001/XMLSchema}anyType">
         *                 &lt;sequence>
         *                   &lt;element name="appId" type="{http://www.w3.org/2001/XMLSchema}string"/>
         *                   &lt;element name="contextId">
         *                     &lt;complexType>
         *                       &lt;simpleContent>
         *                         &lt;extension base="&lt;http://www.w3.org/2001/XMLSchema>string">
         *                           &lt;attribute name="null" type="{http://www.w3.org/2001/XMLSchema}string" />
         *                         &lt;/extension>
         *                       &lt;/simpleContent>
         *                     &lt;/complexType>
         *                   &lt;/element>
         *                   &lt;element name="createdAt" type="{http://www.w3.org/2001/XMLSchema}string"/>
         *                   &lt;element name="updatedAt" type="{http://www.w3.org/2001/XMLSchema}string"/>
         *                   &lt;element name="version" type="{http://www.w3.org/2001/XMLSchema}byte"/>
         *                 &lt;/sequence>
         *               &lt;/restriction>
         *             &lt;/complexContent>
         *           &lt;/complexType>
         *         &lt;/element>
         *         &lt;element name="relationships">
         *           &lt;complexType>
         *             &lt;complexContent>
         *               &lt;restriction base="{http://www.w3.org/2001/XMLSchema}anyType">
         *                 &lt;sequence>
         *                   &lt;element name="deviceSerial" type="{http://www.w3.org/2001/XMLSchema}string"/>
         *                   &lt;element name="driverExternalId" type="{http://www.w3.org/2001/XMLSchema}int"/>
         *                   &lt;element name="driverId" type="{http://www.w3.org/2001/XMLSchema}long"/>
         *                   &lt;element name="stopId" type="{http://www.w3.org/2001/XMLSchema}string"/>
         *                   &lt;element name="workAssignmentId" type="{http://www.w3.org/2001/XMLSchema}string"/>
         *                 &lt;/sequence>
         *               &lt;/restriction>
         *             &lt;/complexContent>
         *           &lt;/complexType>
         *         &lt;/element>
         *         &lt;element name="rules">
         *           &lt;complexType>
         *             &lt;complexContent>
         *               &lt;restriction base="{http://www.w3.org/2001/XMLSchema}anyType">
         *                 &lt;sequence>
         *                   &lt;element name="source" type="{http://www.w3.org/2001/XMLSchema}string"/>
         *                   &lt;element name="targets">
         *                     &lt;complexType>
         *                       &lt;complexContent>
         *                         &lt;restriction base="{http://www.w3.org/2001/XMLSchema}anyType">
         *                           &lt;sequence>
         *                             &lt;element name="element" type="{http://www.w3.org/2001/XMLSchema}string"/>
         *                           &lt;/sequence>
         *                         &lt;/restriction>
         *                       &lt;/complexContent>
         *                     &lt;/complexType>
         *                   &lt;/element>
         *                   &lt;element name="topic" type="{http://www.w3.org/2001/XMLSchema}string"/>
         *                 &lt;/sequence>
         *               &lt;/restriction>
         *             &lt;/complexContent>
         *           &lt;/complexType>
         *         &lt;/element>
         *         &lt;element name="type" type="{http://www.w3.org/2001/XMLSchema}string"/>
         *       &lt;/sequence>
         *     &lt;/restriction>
         *   &lt;/complexContent>
         * &lt;/complexType>
         * </pre>
         * 
         * 
         */
        @XmlAccessorType(XmlAccessType.FIELD)
        @XmlType(name = "", propOrder = {
            "body",
            "docId",
            "meta",
            "relationships",
            "rules",
            "type"
        })
        public static class Value {

            @XmlElement(required = true)
            protected Root.Element.Value.Body body;
            @XmlElement(required = true)
            protected String docId;
            @XmlElement(required = true)
            protected Root.Element.Value.Meta meta;
            @XmlElement(required = true)
            protected Root.Element.Value.Relationships relationships;
            @XmlElement(required = true)
            protected Root.Element.Value.Rules rules;
            @XmlElement(required = true)
            protected String type;

            /**
             * Gets the value of the body property.
             * 
             * @return
             *     possible object is
             *     {@link Root.Element.Value.Body }
             *     
             */
            public Root.Element.Value.Body getBody() {
                return body;
            }

            /**
             * Sets the value of the body property.
             * 
             * @param value
             *     allowed object is
             *     {@link Root.Element.Value.Body }
             *     
             */
            public void setBody(Root.Element.Value.Body value) {
                this.body = value;
            }

            /**
             * Gets the value of the docId property.
             * 
             * @return
             *     possible object is
             *     {@link String }
             *     
             */
            public String getDocId() {
                return docId;
            }

            /**
             * Sets the value of the docId property.
             * 
             * @param value
             *     allowed object is
             *     {@link String }
             *     
             */
            public void setDocId(String value) {
                this.docId = value;
            }

            /**
             * Gets the value of the meta property.
             * 
             * @return
             *     possible object is
             *     {@link Root.Element.Value.Meta }
             *     
             */
            public Root.Element.Value.Meta getMeta() {
                return meta;
            }

            /**
             * Sets the value of the meta property.
             * 
             * @param value
             *     allowed object is
             *     {@link Root.Element.Value.Meta }
             *     
             */
            public void setMeta(Root.Element.Value.Meta value) {
                this.meta = value;
            }

            /**
             * Gets the value of the relationships property.
             * 
             * @return
             *     possible object is
             *     {@link Root.Element.Value.Relationships }
             *     
             */
            public Root.Element.Value.Relationships getRelationships() {
                return relationships;
            }

            /**
             * Sets the value of the relationships property.
             * 
             * @param value
             *     allowed object is
             *     {@link Root.Element.Value.Relationships }
             *     
             */
            public void setRelationships(Root.Element.Value.Relationships value) {
                this.relationships = value;
            }

            /**
             * Gets the value of the rules property.
             * 
             * @return
             *     possible object is
             *     {@link Root.Element.Value.Rules }
             *     
             */
            public Root.Element.Value.Rules getRules() {
                return rules;
            }

            /**
             * Sets the value of the rules property.
             * 
             * @param value
             *     allowed object is
             *     {@link Root.Element.Value.Rules }
             *     
             */
            public void setRules(Root.Element.Value.Rules value) {
                this.rules = value;
            }

            /**
             * Gets the value of the type property.
             * 
             * @return
             *     possible object is
             *     {@link String }
             *     
             */
            public String getType() {
                return type;
            }

            /**
             * Sets the value of the type property.
             * 
             * @param value
             *     allowed object is
             *     {@link String }
             *     
             */
            public void setType(String value) {
                this.type = value;
            }


            /**
             * <p>Java class for anonymous complex type.
             * 
             * <p>The following schema fragment specifies the expected content contained within this class.
             * 
             * <pre>
             * &lt;complexType>
             *   &lt;complexContent>
             *     &lt;restriction base="{http://www.w3.org/2001/XMLSchema}anyType">
             *       &lt;sequence>
             *         &lt;element name="deviceLatitude" type="{http://www.w3.org/2001/XMLSchema}float"/>
             *         &lt;element name="deviceLongitude" type="{http://www.w3.org/2001/XMLSchema}float"/>
             *         &lt;element name="status" type="{http://www.w3.org/2001/XMLSchema}string"/>
             *       &lt;/sequence>
             *     &lt;/restriction>
             *   &lt;/complexContent>
             * &lt;/complexType>
             * </pre>
             * 
             * 
             */
            @XmlAccessorType(XmlAccessType.FIELD)
            @XmlType(name = "", propOrder = {
                "deviceLatitude",
                "deviceLongitude",
                "status"
            })
            public static class Body {

                protected float deviceLatitude;
                protected float deviceLongitude;
                @XmlElement(required = true)
                protected String status;

                /**
                 * Gets the value of the deviceLatitude property.
                 * 
                 */
                public float getDeviceLatitude() {
                    return deviceLatitude;
                }

                /**
                 * Sets the value of the deviceLatitude property.
                 * 
                 */
                public void setDeviceLatitude(float value) {
                    this.deviceLatitude = value;
                }

                /**
                 * Gets the value of the deviceLongitude property.
                 * 
                 */
                public float getDeviceLongitude() {
                    return deviceLongitude;
                }

                /**
                 * Sets the value of the deviceLongitude property.
                 * 
                 */
                public void setDeviceLongitude(float value) {
                    this.deviceLongitude = value;
                }

                /**
                 * Gets the value of the status property.
                 * 
                 * @return
                 *     possible object is
                 *     {@link String }
                 *     
                 */
                public String getStatus() {
                    return status;
                }

                /**
                 * Sets the value of the status property.
                 * 
                 * @param value
                 *     allowed object is
                 *     {@link String }
                 *     
                 */
                public void setStatus(String value) {
                    this.status = value;
                }

            }


            /**
             * <p>Java class for anonymous complex type.
             * 
             * <p>The following schema fragment specifies the expected content contained within this class.
             * 
             * <pre>
             * &lt;complexType>
             *   &lt;complexContent>
             *     &lt;restriction base="{http://www.w3.org/2001/XMLSchema}anyType">
             *       &lt;sequence>
             *         &lt;element name="appId" type="{http://www.w3.org/2001/XMLSchema}string"/>
             *         &lt;element name="contextId">
             *           &lt;complexType>
             *             &lt;simpleContent>
             *               &lt;extension base="&lt;http://www.w3.org/2001/XMLSchema>string">
             *                 &lt;attribute name="null" type="{http://www.w3.org/2001/XMLSchema}string" />
             *               &lt;/extension>
             *             &lt;/simpleContent>
             *           &lt;/complexType>
             *         &lt;/element>
             *         &lt;element name="createdAt" type="{http://www.w3.org/2001/XMLSchema}string"/>
             *         &lt;element name="updatedAt" type="{http://www.w3.org/2001/XMLSchema}string"/>
             *         &lt;element name="version" type="{http://www.w3.org/2001/XMLSchema}byte"/>
             *       &lt;/sequence>
             *     &lt;/restriction>
             *   &lt;/complexContent>
             * &lt;/complexType>
             * </pre>
             * 
             * 
             */
            @XmlAccessorType(XmlAccessType.FIELD)
            @XmlType(name = "", propOrder = {
                "appId",
                "contextId",
                "createdAt",
                "updatedAt",
                "version"
            })
            public static class Meta {

                @XmlElement(required = true)
                protected String appId;
                @XmlElement(required = true)
                protected Root.Element.Value.Meta.ContextId contextId;
                @XmlElement(required = true)
                protected String createdAt;
                @XmlElement(required = true)
                protected String updatedAt;
                protected byte version;

                /**
                 * Gets the value of the appId property.
                 * 
                 * @return
                 *     possible object is
                 *     {@link String }
                 *     
                 */
                public String getAppId() {
                    return appId;
                }

                /**
                 * Sets the value of the appId property.
                 * 
                 * @param value
                 *     allowed object is
                 *     {@link String }
                 *     
                 */
                public void setAppId(String value) {
                    this.appId = value;
                }

                /**
                 * Gets the value of the contextId property.
                 * 
                 * @return
                 *     possible object is
                 *     {@link Root.Element.Value.Meta.ContextId }
                 *     
                 */
                public Root.Element.Value.Meta.ContextId getContextId() {
                    return contextId;
                }

                /**
                 * Sets the value of the contextId property.
                 * 
                 * @param value
                 *     allowed object is
                 *     {@link Root.Element.Value.Meta.ContextId }
                 *     
                 */
                public void setContextId(Root.Element.Value.Meta.ContextId value) {
                    this.contextId = value;
                }

                /**
                 * Gets the value of the createdAt property.
                 * 
                 * @return
                 *     possible object is
                 *     {@link String }
                 *     
                 */
                public String getCreatedAt() {
                    return createdAt;
                }

                /**
                 * Sets the value of the createdAt property.
                 * 
                 * @param value
                 *     allowed object is
                 *     {@link String }
                 *     
                 */
                public void setCreatedAt(String value) {
                    this.createdAt = value;
                }

                /**
                 * Gets the value of the updatedAt property.
                 * 
                 * @return
                 *     possible object is
                 *     {@link String }
                 *     
                 */
                public String getUpdatedAt() {
                    return updatedAt;
                }

                /**
                 * Sets the value of the updatedAt property.
                 * 
                 * @param value
                 *     allowed object is
                 *     {@link String }
                 *     
                 */
                public void setUpdatedAt(String value) {
                    this.updatedAt = value;
                }

                /**
                 * Gets the value of the version property.
                 * 
                 */
                public byte getVersion() {
                    return version;
                }

                /**
                 * Sets the value of the version property.
                 * 
                 */
                public void setVersion(byte value) {
                    this.version = value;
                }


                /**
                 * <p>Java class for anonymous complex type.
                 * 
                 * <p>The following schema fragment specifies the expected content contained within this class.
                 * 
                 * <pre>
                 * &lt;complexType>
                 *   &lt;simpleContent>
                 *     &lt;extension base="&lt;http://www.w3.org/2001/XMLSchema>string">
                 *       &lt;attribute name="null" type="{http://www.w3.org/2001/XMLSchema}string" />
                 *     &lt;/extension>
                 *   &lt;/simpleContent>
                 * &lt;/complexType>
                 * </pre>
                 * 
                 * 
                 */
                @XmlAccessorType(XmlAccessType.FIELD)
                @XmlType(name = "", propOrder = {
                    "value"
                })
                public static class ContextId {

                    @XmlValue
                    protected String value;
                    @XmlAttribute(name = "null")
                    protected String _null;

                    /**
                     * Gets the value of the value property.
                     * 
                     * @return
                     *     possible object is
                     *     {@link String }
                     *     
                     */
                    public String getValue() {
                        return value;
                    }

                    /**
                     * Sets the value of the value property.
                     * 
                     * @param value
                     *     allowed object is
                     *     {@link String }
                     *     
                     */
                    public void setValue(String value) {
                        this.value = value;
                    }

                    /**
                     * Gets the value of the null property.
                     * 
                     * @return
                     *     possible object is
                     *     {@link String }
                     *     
                     */
                    public String getNull() {
                        return _null;
                    }

                    /**
                     * Sets the value of the null property.
                     * 
                     * @param value
                     *     allowed object is
                     *     {@link String }
                     *     
                     */
                    public void setNull(String value) {
                        this._null = value;
                    }

                }

            }


            /**
             * <p>Java class for anonymous complex type.
             * 
             * <p>The following schema fragment specifies the expected content contained within this class.
             * 
             * <pre>
             * &lt;complexType>
             *   &lt;complexContent>
             *     &lt;restriction base="{http://www.w3.org/2001/XMLSchema}anyType">
             *       &lt;sequence>
             *         &lt;element name="deviceSerial" type="{http://www.w3.org/2001/XMLSchema}string"/>
             *         &lt;element name="driverExternalId" type="{http://www.w3.org/2001/XMLSchema}int"/>
             *         &lt;element name="driverId" type="{http://www.w3.org/2001/XMLSchema}long"/>
             *         &lt;element name="stopId" type="{http://www.w3.org/2001/XMLSchema}string"/>
             *         &lt;element name="workAssignmentId" type="{http://www.w3.org/2001/XMLSchema}string"/>
             *       &lt;/sequence>
             *     &lt;/restriction>
             *   &lt;/complexContent>
             * &lt;/complexType>
             * </pre>
             * 
             * 
             */
            @XmlAccessorType(XmlAccessType.FIELD)
            @XmlType(name = "", propOrder = {
                "deviceSerial",
                "driverExternalId",
                "driverId",
                "stopId",
                "workAssignmentId"
            })
            public static class Relationships {

                @XmlElement(required = true)
                protected String deviceSerial;
                protected int driverExternalId;
                protected long driverId;
                @XmlElement(required = true)
                protected String stopId;
                @XmlElement(required = true)
                protected String workAssignmentId;

                /**
                 * Gets the value of the deviceSerial property.
                 * 
                 * @return
                 *     possible object is
                 *     {@link String }
                 *     
                 */
                public String getDeviceSerial() {
                    return deviceSerial;
                }

                /**
                 * Sets the value of the deviceSerial property.
                 * 
                 * @param value
                 *     allowed object is
                 *     {@link String }
                 *     
                 */
                public void setDeviceSerial(String value) {
                    this.deviceSerial = value;
                }

                /**
                 * Gets the value of the driverExternalId property.
                 * 
                 */
                public int getDriverExternalId() {
                    return driverExternalId;
                }

                /**
                 * Sets the value of the driverExternalId property.
                 * 
                 */
                public void setDriverExternalId(int value) {
                    this.driverExternalId = value;
                }

                /**
                 * Gets the value of the driverId property.
                 * 
                 */
                public long getDriverId() {
                    return driverId;
                }

                /**
                 * Sets the value of the driverId property.
                 * 
                 */
                public void setDriverId(long value) {
                    this.driverId = value;
                }

                /**
                 * Gets the value of the stopId property.
                 * 
                 * @return
                 *     possible object is
                 *     {@link String }
                 *     
                 */
                public String getStopId() {
                    return stopId;
                }

                /**
                 * Sets the value of the stopId property.
                 * 
                 * @param value
                 *     allowed object is
                 *     {@link String }
                 *     
                 */
                public void setStopId(String value) {
                    this.stopId = value;
                }

                /**
                 * Gets the value of the workAssignmentId property.
                 * 
                 * @return
                 *     possible object is
                 *     {@link String }
                 *     
                 */
                public String getWorkAssignmentId() {
                    return workAssignmentId;
                }

                /**
                 * Sets the value of the workAssignmentId property.
                 * 
                 * @param value
                 *     allowed object is
                 *     {@link String }
                 *     
                 */
                public void setWorkAssignmentId(String value) {
                    this.workAssignmentId = value;
                }

            }


            /**
             * <p>Java class for anonymous complex type.
             * 
             * <p>The following schema fragment specifies the expected content contained within this class.
             * 
             * <pre>
             * &lt;complexType>
             *   &lt;complexContent>
             *     &lt;restriction base="{http://www.w3.org/2001/XMLSchema}anyType">
             *       &lt;sequence>
             *         &lt;element name="source" type="{http://www.w3.org/2001/XMLSchema}string"/>
             *         &lt;element name="targets">
             *           &lt;complexType>
             *             &lt;complexContent>
             *               &lt;restriction base="{http://www.w3.org/2001/XMLSchema}anyType">
             *                 &lt;sequence>
             *                   &lt;element name="element" type="{http://www.w3.org/2001/XMLSchema}string"/>
             *                 &lt;/sequence>
             *               &lt;/restriction>
             *             &lt;/complexContent>
             *           &lt;/complexType>
             *         &lt;/element>
             *         &lt;element name="topic" type="{http://www.w3.org/2001/XMLSchema}string"/>
             *       &lt;/sequence>
             *     &lt;/restriction>
             *   &lt;/complexContent>
             * &lt;/complexType>
             * </pre>
             * 
             * 
             */
            @XmlAccessorType(XmlAccessType.FIELD)
            @XmlType(name = "", propOrder = {
                "source",
                "targets",
                "topic"
            })
            public static class Rules {

                @XmlElement(required = true)
                protected String source;
                @XmlElement(required = true)
                protected Root.Element.Value.Rules.Targets targets;
                @XmlElement(required = true)
                protected String topic;

                /**
                 * Gets the value of the source property.
                 * 
                 * @return
                 *     possible object is
                 *     {@link String }
                 *     
                 */
                public String getSource() {
                    return source;
                }

                /**
                 * Sets the value of the source property.
                 * 
                 * @param value
                 *     allowed object is
                 *     {@link String }
                 *     
                 */
                public void setSource(String value) {
                    this.source = value;
                }

                /**
                 * Gets the value of the targets property.
                 * 
                 * @return
                 *     possible object is
                 *     {@link Root.Element.Value.Rules.Targets }
                 *     
                 */
                public Root.Element.Value.Rules.Targets getTargets() {
                    return targets;
                }

                /**
                 * Sets the value of the targets property.
                 * 
                 * @param value
                 *     allowed object is
                 *     {@link Root.Element.Value.Rules.Targets }
                 *     
                 */
                public void setTargets(Root.Element.Value.Rules.Targets value) {
                    this.targets = value;
                }

                /**
                 * Gets the value of the topic property.
                 * 
                 * @return
                 *     possible object is
                 *     {@link String }
                 *     
                 */
                public String getTopic() {
                    return topic;
                }

                /**
                 * Sets the value of the topic property.
                 * 
                 * @param value
                 *     allowed object is
                 *     {@link String }
                 *     
                 */
                public void setTopic(String value) {
                    this.topic = value;
                }


                /**
                 * <p>Java class for anonymous complex type.
                 * 
                 * <p>The following schema fragment specifies the expected content contained within this class.
                 * 
                 * <pre>
                 * &lt;complexType>
                 *   &lt;complexContent>
                 *     &lt;restriction base="{http://www.w3.org/2001/XMLSchema}anyType">
                 *       &lt;sequence>
                 *         &lt;element name="element" type="{http://www.w3.org/2001/XMLSchema}string"/>
                 *       &lt;/sequence>
                 *     &lt;/restriction>
                 *   &lt;/complexContent>
                 * &lt;/complexType>
                 * </pre>
                 * 
                 * 
                 */
                @XmlAccessorType(XmlAccessType.FIELD)
                @XmlType(name = "", propOrder = {
                    "element"
                })
                public static class Targets {

                    @XmlElement(required = true)
                    protected String element;

                    /**
                     * Gets the value of the element property.
                     * 
                     * @return
                     *     possible object is
                     *     {@link String }
                     *     
                     */
                    public String getElement() {
                        return element;
                    }

                    /**
                     * Sets the value of the element property.
                     * 
                     * @param value
                     *     allowed object is
                     *     {@link String }
                     *     
                     */
                    public void setElement(String value) {
                        this.element = value;
                    }

                }

            }

        }

    }

}
