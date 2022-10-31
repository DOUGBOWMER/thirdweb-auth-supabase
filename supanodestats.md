secret="is Connected? SupabaseClient {
supabaseUrl: 'https://laxtrztojlsqsbgalkgp.supabase.co',
supabaseKey: 'eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJpc3MiOiJzdXBhYmFzZSIsInJlZiI6Indyc3B5bGdlenN0Y21hYnlicmJoIiwicm9sZSI6InNlcnZpY2Vfcm9sZSIsImlhdCI6MTY2NjE2ODUxNiwiZXhwIjoxOTgxNzQ0NTE2fQ.wN5xvT9UI5LxVu2cetEG3tdx0YBeWCwCB23L6M5k0XI',
realtimeUrl: 'wss://laxtrztojlsqsbgalkgp.supabase.co/realtime/v1',
authUrl: 'https://laxtrztojlsqsbgalkgp.supabase.co/auth/v1',
storageUrl: 'https://laxtrztojlsqsbgalkgp.supabase.co/storage/v1',
functionsUrl: 'https://laxtrztojlsqsbgalkgp.functions.supabase.co',
storageKey: 'sb-laxtrztojlsqsbgalkgp-auth-token',
headers: { 'X-Client-Info': 'supabase-js/2.0.3' },
auth: SupabaseAuthClient {
stateChangeEmitters: Map(1) { 'fa5f6aaa-8f83-45e0-934b-32fe13bb3f1b' => [Object] },
networkRetries: 0,
refreshingDeferred: null,
initializePromise: Promise { <pending> },
detectSessionInUrl: true,
inMemorySession: null,
storageKey: 'sb-laxtrztojlsqsbgalkgp-auth-token',
autoRefreshToken: true,
persistSession: true,
storage: {
getItem: [Function: getItem],
setItem: [Function: setItem],
removeItem: [Function: removeItem]
},
admin: GoTrueAdminApi {
url: 'https://laxtrztojlsqsbgalkgp.supabase.co/auth/v1',
headers: [Object],
fetch: [Function (anonymous)],
mfa: [Object]
},
url: 'https://laxtrztojlsqsbgalkgp.supabase.co/auth/v1',
headers: {
Authorization: 'Bearer eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJpc3MiOiJzdXBhYmFzZSIsInJlZiI6Indyc3B5bGdlenN0Y21hYnlicmJoIiwicm9sZSI6InNlcnZpY2Vfcm9sZSIsImlhdCI6MTY2NjE2ODUxNiwiZXhwIjoxOTgxNzQ0NTE2fQ.wN5xvT9UI5LxVu2cetEG3tdx0YBeWCwCB23L6M5k0XI',
apikey: 'eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJpc3MiOiJzdXBhYmFzZSIsInJlZiI6Indyc3B5bGdlenN0Y21hYnlicmJoIiwicm9sZSI6InNlcnZpY2Vfcm9sZSIsImlhdCI6MTY2NjE2ODUxNiwiZXhwIjoxOTgxNzQ0NTE2fQ.wN5xvT9UI5LxVu2cetEG3tdx0YBeWCwCB23L6M5k0XI',
'X-Client-Info': 'supabase-js/2.0.3'
},
fetch: [Function (anonymous)],
mfa: {
verify: [Function: bound _verify],
enroll: [Function: bound _enroll],
unenroll: [Function: bound _unenroll],
challenge: [Function: bound _challenge],
listFactors: [Function: bound _listFactors],
getAuthenticatorAssuranceLevel: [Function: bound _getAuthenticatorAssuranceLevel]
}
},
fetch: [Function (anonymous)],
realtime: RealtimeClient {
accessToken: null,
channels: [],
endPoint: 'wss://laxtrztojlsqsbgalkgp.supabase.co/realtime/v1/websocket',
headers: { 'X-Client-Info': 'supabase-js/2.0.3' },
params: {
apikey: 'eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJpc3MiOiJzdXBhYmFzZSIsInJlZiI6Indyc3B5bGdlenN0Y21hYnlicmJoIiwicm9sZSI6InNlcnZpY2Vfcm9sZSIsImlhdCI6MTY2NjE2ODUxNiwiZXhwIjoxOTgxNzQ0NTE2fQ.wN5xvT9UI5LxVu2cetEG3tdx0YBeWCwCB23L6M5k0XI'
},
timeout: 10000,
transport: [Function: W3CWebSocket],
heartbeatIntervalMs: 30000,
heartbeatTimer: undefined,
pendingHeartbeatRef: null,
ref: 0,
logger: [Function: noop],
conn: null,
sendBuffer: [],
serializer: Serializer { HEADER_LENGTH: 1 },
stateChangeCallbacks: { open: [], close: [], error: [], message: [] },
eventsPerSecondLimitMs: 100,
inThrottle: false,
reconnectAfterMs: [Function (anonymous)],
encode: [Function (anonymous)],
decode: [Function: bound decode],
reconnectTimer: Timer {
callback: [Function (anonymous)],
timerCalc: [Function (anonymous)],
timer: undefined,
tries: 0
}
},
rest: PostgrestClient {
url: 'https://laxtrztojlsqsbgalkgp.supabase.co/rest/v1',
headers: { 'X-Client-Info': 'supabase-js/2.0.3' },
schema: 'public',
fetch: [Function (anonymous)]
}
}
"
