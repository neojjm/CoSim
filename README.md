⋄ _PAL_ NRESULT Plugin_Init(
LPCOMPONENT_INFO pCmpInfo);
⋄ _PAL_ NRESULT Plugin_End();
⋄ _PAL_ NRESULT Protocol_Init(
Session *lpSsn);
⋄ _PAL_ NRESULT Protocol_End(
Session *lpSsn);
⋄ _PAL_ NRESULT Protocol_Handle_Event(
Session *lpSsn, Event *lpEvt);
⋄ _PAL_ NRESULT Protocol_Handle_Packet(
Session *lpSsn, Packet *lpPkt);
Based on above functions, VPSI can manage
