# Aplazo Components

VTEX Aplazo Widgets 

## Configuration for Product Detail Page on VTEX IO

### Step 1 - Installing the Aplazo Components

Using your terminal, log in to the desired VTEX account and run the following command:

`vtex install aplazo.aplazo-components@0.x`

### Step 2 - Adding dependencies to your store theme

Add `"aplazo.aplazo-components": "0.x"` to your store-theme peer dependencies.

### Step 3 - Declaring the app's blocks in your store theme

Once the app is configured, it is time to place the following block in your Store Theme app:

- `aplazo-placement` - This block can be added to the product page template (`store.product`). It renders a message that will show the amount and payment term for the product, even before adding it to the shopping cart.

### Step 4 - Defining the app settings

1. In the account's admin dashboard, access `Apps > My Apps` and then click on the box for `Aplazo`:


2. Once in the app's settings page, define the following settings according to the desired scenario:

![import-container](https://aplazo.s3.us-west-1.amazonaws.com/sdk/vtex.component.assets/aplazo-admin-myapps-aplazo.png)

## Configuration for Product Detail Page CMS

### Step 1 - Download GTM container

Download GTM [container](https://aplazo.s3.us-west-1.amazonaws.com/sdk/vtex.component.assets/GTM-aplazo-container.json) this json contains tags and triggers for aplazo components

### Step 2 - Import container into your GTM account

After signed in you GTM account go to Admin > Import Container

![import-container](https://aplazo.s3.us-west-1.amazonaws.com/sdk/vtex.component.assets/gtm_1.png)

Upload the json file that was downloaded on step 1 and select the workspace from where you want to import the container

![upload-container](https://aplazo.s3.us-west-1.amazonaws.com/sdk/vtex.component.assets/gtm_2.png)

![select-workspace](https://aplazo.s3.us-west-1.amazonaws.com/sdk/vtex.component.assets/gtm_3.png)

Confirm and publish changes
