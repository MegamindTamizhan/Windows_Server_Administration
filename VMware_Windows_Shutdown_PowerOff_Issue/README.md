# Log Name: System, Source: Microsoft-Windows-Kernel-Power, Event ID: 109, Description: The kernel power manager has initiated a shutdown transition.

        > Is your Windows license expired? Did you activate the license?
        > Can you try to Replace the PSU and see if the problem goes away? -> Open an admin command prompt and run powercfg /systempowerreport . See if the report gives any more clues on what is triggering it.

        $ PS C:\> powercfg /systempowerreport
        $ Sleep Study report saved to file path C:\sleepstudy-report.html.
        $ PS C:\>

