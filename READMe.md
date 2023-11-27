# Configuring Advanced Network Security with OPNsense Sensei

This project delves into the configuration and utilization of OPNsense
Sensei, a powerful firewall module designed for advanced network
security. The primary focus is on tailoring Sensei to monitor and
control the Network, encompassing tasks such as interface
configuration, rule establishment, and security posture adjustments. The
subsequent steps provide a detailed exploration of each facet, combining
practical application with meticulous documentation through screenshots.
This hands-on experience aims to enhance proficiency in leveraging
advanced firewall features for targeted network management.

**Task 1: Sensei Configuration for Guest Network Monitoring**

- **Navigation to Sensei Configuration:**

  - I initiated the configuration process by navigating to the Sensei
    module within the OPNsense firewall.

<!-- -->

- **Guest Network Selection:**

  - The first task involved selecting the Guest Network as the exclusive
    network for monitoring by Sensei.

- **Implementation of Configuration Changes:**

  - After selecting the Guest Network, I implemented the necessary
    configuration changes to ensure Sensei focused on monitoring this
    specific network.

**The following figures shows the initial configuration of Opnsense
Sensei to monitor the Guest Network interface:**

<img src="./media/image1.png" style="width:6.5in;height:5.39861in" />

<img src="./media/image2.png" style="width:6.5in;height:5.00278in" />

<img src="./media/image3.png" style="width:6.5in;height:5.00903in" />

<img src="./media/image4.png" style="width:6.5in;height:5.00278in" />

<img src="./media/image5.png" style="width:6.5in;height:5.39236in" />

**Task 2: Dashboard Verification**

- **Access to Sensei Dashboard:**

  - I accessed the Sensei dashboard to review and verify the applied
    changes.

<!-- -->

- **Confirmation of Guest Network Display:**

  - To ensure that only the Guest Network interface was being monitored,
    I inspected the dashboard, confirming the accuracy of the applied
    settings.

**The following figures illustrates the Dashboards showing the
GuestNetwork interface being monitored:**

<img src="./media/image6.png" style="width:6.5in;height:5.43264in" />

<img src="./media/image7.png" style="width:6.5in;height:5.41319in" />

<img src="./media/image8.png" style="width:6.5in;height:5.40486in" />

**Task 3: Interface Monitoring Confirmation**

- **Navigation to Interface Settings:**

  - I went into the interface settings within Sensei to validate the
    configuration and confirm the monitoring of the Guest Network.

<!-- -->

- **Verification of Guest Network Display:**

  - Within the interface settings, I verified that the Guest Network
    interface was visibly monitored, ensuring Sensei was accurately
    configured. This is illustrated in the following screenshot taken
    from the project.

<img src="./media/image9.png" style="width:6.5in;height:5.42639in" />

**Task 4: Rule Configuration for Google and Nike Access**

- **Creation of Rule in Sensei:**

  - I created a specific rule in Sensei allowing the Guest Network to
    access Google while preventing access to nike.com as illustrated in
    the following figure.

> <img src="./media/image10.png" style="width:6.5in;height:5.38611in" />

- **Access Verification:**

  - Screenshots were taken to demonstrate the effectiveness of the rule,
    including PC1 successfully accessing nike.com and PC2 being
    restricted from accessing nike.com.

> <img src="./media/image11.png" style="width:6.5in;height:5.39236in" />

<img src="./media/image12.png" style="width:6.5in;height:5.41319in" />

- **Logging Rule Activities:**

  - I captured screenshots of the log file and block report in Sensei to
    document the activities and outcomes of the configured rule.

> <img src="./media/image13.png" style="width:6.5in;height:5.36042in" />

**Task 5: Web Filter Security Posture Modification**

- **Modification of Web Filter Security Posture:**

  - I adjusted the security posture of the Web Filter within Sensei from
    Permissive to High Control.

> <img src="./media/image14.png" style="width:6.5in;height:5.43264in" />

**Task 6: Modify Dashboard to Include Blocked Host**

- **Configuration of Dashboard:**

  - I edited the settings of the dashboard to incorporate information
    about blocked hosts, providing a comprehensive view.

<img src="./media/image15.png" style="width:6.5in;height:5.42014in" />

<img src="./media/image16.png" style="width:6.5in;height:5.39444in" />

- **Rule Configuration for Blocking Sites:**

  - Screenshots were taken during the configuration of rules to block
    specific sites such as Tinder.com, Callofduty.com, and
    Bittorrent.com.

> <img src="./media/image17.png" style="width:6.5in;height:5.42639in" />

- **Verification of Blocked Sites:**

  - Screenshots were captured to showcase the successful blocking of
    each site as indicated by Sensei.

> <img src="./media/image18.png" style="width:6.5in;height:5.41319in" />
>
> <img src="./media/image19.png" style="width:6.5in;height:5.40694in" />
>
> <img src="./media/image20.png" style="width:6.5in;height:5.41319in" />

- **Dashboard Configuration Verification:**

  - I ensured that the dashboard accurately reflected the status of
    blocked and allowed sites, validating the effectiveness of the
    configured rules.

> <img src="./media/image21.png" style="width:6.5in;height:5.38611in" />

**Conclusion:**

In this comprehensive lab, each step was meticulously performed and
documented. The accompanying screenshots serve as visual evidence,
providing clarity and transparency in the configuration of OPNsense
Sensei for Network monitoring and rule implementation. This
hands-on experience has enriched my understanding of advanced firewall
features.
