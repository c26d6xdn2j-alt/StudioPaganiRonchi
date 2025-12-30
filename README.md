# StudioPaganiRonchi
Studio Pagani Ronchi srl

## Website

This repository contains the official website for Studio Pagani Ronchi, a dental and aesthetic medicine practice in Telgate, BG, Italy.

## Google Reviews Widget Configuration

The website includes a Google Reviews widget in the "Dove Siamo" (Where We Are) section. To complete the setup:

1. **Update the Google Place ID**: Replace `YOUR_GOOGLE_PLACE_ID` in the review link (line ~344 in index.html) with your actual Google My Business Place ID.
   
   Find your Place ID at: https://developers.google.com/maps/documentation/places/web-service/place-id

2. **Review Link Format**: 
   ```
   https://g.page/r/YOUR_GOOGLE_PLACE_ID/review
   ```

3. **Embedded Reviews**: The current implementation uses a Google Maps embed. For a more sophisticated reviews display, consider using:
   - Google's official Place Reviews API
   - Third-party widgets like Elfsight, EmbedSocial, or Tagembed
   - Custom implementation using the Google Places API

## Features

- Responsive design for mobile and desktop
- Google Reviews integration
- Contact information and appointment booking
- Service descriptions
- Operating hours
- Google Maps location embed
