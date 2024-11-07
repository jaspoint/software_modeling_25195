# software_modeling_25195 Ndacyayisenga Shema Arsene

Short specification:
1. System Off- Well, the traffic light system begins with the "System Off.
2. E-W Green N-S Red- The E-W light turns green and the N-S light is red. This state of affairs until the "East-West Green time" runs out.
3. East-West Yellow (North-South Red) - The green time is over, so the light is now yellow for East-West traffic, but North-South traffic still has a red light. This state of affairs persists until the "East-West Yellow duration" timer elapses.
4. Green Light (North-South) Red Light (East-West) - The light is green going North-South and red East-West. This state persists until the "North-South Green time" runs out.
5. NS YELLOW (EW RED) - The green time expires, and the light turns yellow for North-South traffic, red still for East-West. This state lasts until the "North-South Yellow duration" timer runs out.
6. Loop* - The cycle starts again at East-West green when both yellows run out so that the North-South and East-West directions always have opposing traffic.
The timers that control the transition from one state to the next depend on the length of time the green light and yellow light are on for each direction.
