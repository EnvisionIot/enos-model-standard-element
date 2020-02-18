# enos-model-standard-element

This repo provides nearly two thousand Standard Features for EnOS™ Model. 

<b>EnOS Standard Feature Library</b> is based on IEC, ICA, OMA and other industry standards, providing standardized device feature definitions, helping developers to achieve standardization across models, unifying data definitions for the same features, and facilitating subsequent data processing and interworking. At the same time, model creators can create models based on Standard Feature Library, which enables reuse of features and can improve the efficiency of model construction.

## Dependencies

+ Envision EnOS™ 2.1.0 or newer

## Installation & Update

There are two ways to import Standard Features Library:

### Method 1. One Click Import (Recommended)

You can import the latest version of Standard Features Library on EnOS™ Console directly.

+ Step 1. Open page `System Management` / `Model Management` / `Standard Function` on EnOS™;
+ Step 2. Click button `Check Update`:
  - If this is your first time to import Standard Features, or your current version is older than the latest one, you will see "New version available. Do you want an update？" in the popup.
    Choose `yes` and the latest Standard Features will be imported in a minute.
  - Otherwise, you will see the prompt "Latest version already installed".

### Method 2. Manual Import

If the EnOS™ Console can't access to github, you need to download Standard Features resource pack from [github](https://github.com/EnvisionIot/enos-model-standard-element) and Import it on EnOS™ Console manually.

+ Step 1. Click `Clone of download` -> `Download Zip` on github, you will obtain the latest "enos-mqtt-sdk-python-master.zip";
+ Step 2. Open page `System Management` / `Model Management` / `Standard Function` on EnOS™ Console;
+ Step 3. Click button `Import Resource Pack` -> `OK`;
+ Step 4. Click button `Upload File` in the popup and select the resource pack obtained in Step 1;
+ Step 5. Click `OK`, then the latest Standard Features will be imported in a minute.

These steps are also available for updating Standard Features Library to the latest version.

## Usage

When adding a new feature to a model, a Standard Feature can be adopted, and it may help you save a lot of time;
You can use a Standard Feature as follows:

+ Step 1. In the EnOS Console, select a model and click icon `Edit`, then click tab `Feature Definition` in the `Model Details` screen;
+ Step 2. Click button `Edit` and start editing the model draft;
+ Step 3. Click button `Add`, click `Import From Standard Feature Library` in the popup;
+ Step 4. Choose a proper Standard Feature in the list, click button `OK`;
+ Step 5. Fill `Name` and `Idetifier` in the popup, Click button `Confirm` to finish the edition.

## Release Notes

Release notes of `enos-model-standard-element`:

+ 1.0.0(2020/1/6, latest): Official release.
+ 0.9.3(2019/12/27): Initial release.
