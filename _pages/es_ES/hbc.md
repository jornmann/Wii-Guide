---
title: "Instalación del Canal Homebrew y de BootMii"
---

{% include toc title="Tabla de contenido" %}

Si necesitas ayuda para seguir los pasos de esta guía, por favor solicita ayuda en nuestro [servidor de Discord](https://discord.gg/rc24) (recomendado) o [envíanos un correo electrónico a support@riiconnect24.net](mailto:support@riiconnect24.net).
{: .notice--info}

![Logotipo del Canal Homebrew](/images/hbc.png)

El Canal Homebrew es desde donde iniciarás las aplicaciones homebrew. BootMii es un software que puede respaldar y restaurar la memoria interna de tu Wii, y si está instalado como boot2, brinda protección contra bricks.

#### Instrucciones

1. Verás una pantalla de advertencia contra estafa. Espera 30 segundos hasta que aparezca el texto "Press 1 to continue", y después oprime el botón 1. ![Pantalla de advertencia contra estafa](/images/hackmii/scam.png)
1. You will be presented with a test results screen. Select `Continue`. ![Resultados](/images/hackmii/test_results.png)

If BootMii says that it `can only be installed as an IOS`, that's normal.
{: .notice--info}

1. Select `Install the Homebrew Channel`. ![Homebrew Channel installation](/images/hackmii/hbc_install.png) ![Homebrew Channel installation OK](/images/hackmii/hbc_install_ok.png)
1. Select `Continue` when finished.
1. Once installed, select `Back`, then select `BootMii`. ![BootMii](/images/hackmii/bootmii_install.png)
1. Select `Install BootMii as IOS`.

If you do not have an SD card, you cannot install nor use BootMii, and therefore will not be able to utilize any of the mentioned benefits. <br> You can always [install it at a later date](hackmii).
{: .notice--warning}

![BootMii installation](/images/hackmii/bootmii_install1.png) ![BootMii SD card prompt](/images/hackmii/bootmii_install2.png) ![BootMii SD card preparation](/images/hackmii/bootmii_install3.png) ![BootMii installation OK](/images/hackmii/bootmii_install_ok.png)
1. Once done, select `Continue`.
1. If you have the option to `Install BootMii as boot2`, please do so as well. This offers the best possible brick protection you can have. <br> Otherwise, skip this step.
1. Select `Exit` to finally open the Homebrew Channel.


#### Required Reading

You can now use the Homebrew Channel to launch homebrew apps. Open Shop Channel is a one-stop shop for downloading homebrew, which you will learn how to install further in this guide.

Here's a tip - when installing homebrew applications on your SD Card or USB drive, your folder structure should look like this:

![Proper SD Card Folder Structure](images/Wii/FolderStructure.png)

`AppName1` and `AppName2` are placeholder names. Do not nest multiple `apps` folders inside the `apps` folder itself.

[Continue to making a NAND Backup using BootMii](bootmii)<br> Making a NAND backup with BootMii at this point is highly recommended.
{: .notice--info}

If you couldn't install BootMii, continue to [installing Priiloader](priiloader).
{: .notice--info}

Tip: You can tell if a Wii has BootMii installed as boot2 if your disc drive flashes very briefly, only after the immediate flash that happens when you press the POWER Button.
{: .notice--info}
