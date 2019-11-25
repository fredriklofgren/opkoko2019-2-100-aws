# 100% AWS från ruta 0

## Admins
Filen `permissionsAdmins.yaml` är den slutliga filen. `rootAdmins.yaml` har bristen att Alice kan skapa upp Eve som kan ta bort Bob.

Filerna `boundedEvil.yaml` samt `evilAdmin.yaml` kan användas för att påvisa brister i templates.

## Directory, Workmail och Workspaces
Varken Workspaces eller Workmail kan sättas upp med template. Ett enskilt Workspace för en användare kan sättas upp med template (visas i `workspace.yaml`. Directory kan sättas upp med template vilket visas i `directory.yaml`. Både workspace och workmail kräver en nyckel. En för varke tjänst skapas upp i `workmailkey.yaml`respektive `workspacekey.yaml`. I `readrole.yaml` skapas en roll som kan användas för att låta en användare skapd i directory assuma för att logga in i consolen.

