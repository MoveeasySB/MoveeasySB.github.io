  <div className="font-semibold">{s.name}</div>
       <div>Route-Test</div>
                    </Popup>
                  </Marker>
                </React.Fragment>
              ))}

            {route && <Polyline positions={route.line} dashArray="5" />}
          </MapContainer>
        </section>

        {/* Footer-ish info area */}
        <section className="mt-6 grid md:grid-cols-3 gap-4">
          <div className="bg-white p-4 rounded shadow">
            <h4 className="font-semibold">Routenfinder</h4>
            <p className="text-sm text-slate-600">Demo-Routing mit Dummy-Daten — für echte Routen integriere eine Routing-API (z. B. OSRM, GraphHopper, Google Directions)</p>
          </div>

          <div className="bg-white p-4 rounded shadow">
            <h4 className="font-semibold">Nachhaltigkeit</h4>
            <p className="text-sm text-slate-600">Zeige CO₂-Ersparnis zwischen verschiedenen Verkehrsmitteln an (Beispielwerte)</p>
          </div>

          <div className="bg-white p-4 rounded shadow">
            <h4 className="font-semibold">Testphase</h4>
            <p className="text-sm text-slate-600">Live-Daten sind in dieser Testversion nicht enthalten — nur Dummy-Informationen.</p>
          </div>
        </section>
      </main>

      <footer className="mt-8 bg-white py-4">
        <div className="max-w-6xl mx-auto px-4 text-sm text-slate-600">© Move Easy — Prototype</div>
      </footer>
    </div>
  );}
